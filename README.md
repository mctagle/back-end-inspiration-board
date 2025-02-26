# Inspiration Board - Back End
Completed by Camila and Daria in a team of 4 including Sorida and Dana

### [Project Requirements](https://github.com/ada-c17/full-stack-inspiration-board)

The goal of the project is to create a digital inspiration board where users can add motivational "notes". 

## [Front-end deployment](https://migrationmess-front-end.herokuapp.com/)
## [Back-end deployment](https://insp-board-migrationmess.herokuapp.com/boards)
## [Front-end Github Repo](https://github.com/mctagle/front-end-inspiration-board)

## Initial Set up:
This scaffold includes the following:

### `app/__init__.py`

This file configures the app. It's where:

We expect developers to modify this file by:

- Replacing the database connection string
- Importing all models
- Registering all blueprints

Note that `create_app` also uses CORS. There is no extra action needed to be done with CORS.

### `app/routes.py`

We expect endpoints to be defined here.

The file already imports:

- `Blueprint`
- `request`
- `jsonify`
- `make_response`
- `db`

Feel free to alter these import statements.

This file also has a comment to define a Blueprint. Feel free to delete it.

### `app/models` Directory

This project already includes `app/models/board.py` and `app/models/card.py`, to anticipate the models `Board` and `Card`.

Both files already import `db`, for convenience!

### `requirements.txt`

This file lists the dependencies we anticipate are needed for the project.

### `Procfile`

This file already has the contents needed for a Heroku deployment.

If the `create_app` function in `app/__init__.py` is renamed or moved, the contents of this file need to change. Otherwise, we don't anticipate this file to change.
