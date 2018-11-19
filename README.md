# PITCH Game
## This is an application that allows users to make pitches,comment and view the pitches.Done on 16/11/2018


## By **[Francis Sakwa](https://github.com/FrancisSakwa89)**

## Description
 [pitch](https://pitch-5.herokuapp.com/)This is a web application that allows users to submit a pitch. Also, other users are allowed to vote on submitted pitches and leave comments to give their feedback on the pitches. For a user to submit a pitch, vote on a pitch or give feedback on a pitch they need to have an account. <br>

The pitches are organized by categories. Examples of categories: <br> 
- pickup lines
- interview pitches
- product pitches
- promotion pitches

## User Stories
As a user I would like:
* to view the different categories
* to see the pitches other people have posted
* to submit a pitch in any category
* to comment on the different pitches and leave feedback
* to vote on the pitch and give it a downvote or upvote

## Specifications
| Behavior        | Input           | Output  |
| ------------- |:-------------:| -----:|
| Click On Register | Your email : franco@gmail.com.com <br> Username : franco <br> Password : francis | New user is registered |
| Sign in/Log in | Your email : franco@gmail.com <br> Password : francis | Signed in |
| Display pitch categories | Categories display on navbar | List of various pitch categories |
| See pitches from selected category | **Click** a category | Navigates to the selected category |
| Create a pitch | **Click On Time To pitch** | The authenticated user is navigated to the pitch form to fill in |
| Comment on a pitch | **Click Comment** | User navigates to the comment form  |

## Setup/Installation Requirements

* Click [Pitch](https://pitch-5.herokuapp.com/) <br/>
  or <br/>
* Copy [Pitch ](https://pitch-5.herokuapp.com/) and  Paste the link on your prefered browser

_*This requires internet connection._*

# Running Tests
* python3.6 manage.py test

## Known Bugs

- Unable to make vote counts


## Technologies Used
- Python3.6
- Flask
- Bootstrap
- Postgres Database
- CSS
- HTML

### License

[MIT License](https://choosealicense.com/licenses/mit/#) copy;2018 [Francis Sakwa](https://github.com/FrancisSakwa89/)
