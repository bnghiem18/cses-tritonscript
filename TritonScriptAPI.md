# TritonScript API Documentation

# Schemas
## Note

## Event

## StudyGroup

## User

# Route Categories

## Users 
### GET `/api/user/`

### POST `/api/user/update/:id`

### DELETE`/api/user/delete/:id`

## Notes

### GET `/api/note/`
Returns a list of all notes, sorted by their latest update in the database.

### GET `/api/note/search/:name`
Searches all notes by name, returning a list of all notes which contain the string `:name`.

### POST `/:id`
Create a new note object with id `:id`.

## Events

### GET `/api/event/events`
Returns a list of all events, sorted by the date and time of the event.

### GET `/api/event/:name`
Searches all events by name, returning a list of all notes which contain the string `:name`.

### POST `/api/event/:id`
Create a new event object with id `:id`.

## Study Groups

### GET `/api/studygroup/all`
Returns a list of all study groups, sorted by their latest update in the database.

### GET `/api/studygroup/search/:name`
Searches all study groups by name, returning a list of all study groups which contain the string `:name`.

### POST `/api/studygroup/:id`
Create a new study group object with id `:id`.
