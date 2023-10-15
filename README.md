# APP

GymPass style app

## RFs (Functional Requirements)

- [] It must be possible to register.
- [] It must be possible to authenticate.
- [] It must be possible to retrieve the profile of a logged-in user.
- [] It must be possible to retrieve the number of check-ins performed by the logged-in user.
- [] It must be possible for the user to access their check-in history.
- [] It must be possible for the user to search for nearby gyms.
- [] It must be possible for the user to search for gyms by name.
- [] It must be possible for the user to check in at a gym.
- [] It must be possible to validate a user's check-in.
- [] It must be possible to register a gym.

## RNs (Business Rules)

- [ ] The user should not be able to register with a duplicated email.
- [ ] The user cannot make 2 check-ins on the same day.
- [ ] The user cannot check in if not within 100 meters of the gym.
- [ ] The check-in can only be validated up to 20 minutes after creation.
- [ ] The check-in can only be validated by administrators.
- [ ] Gyms can only be registered by administrators.

## RNFs (Non-Functional Requirements)

- [ ] The user's password needs to be encrypted.
- [ ] Application data must be persisted in a PostgreSQL database.
- [ ] All data lists must be paginated with 20 items per page.
- [ ] The user must be identified by a JSON Web Token (JWT).
