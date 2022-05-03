# Simple Miro Tool
This is a github pages page hosted here:
https://chrispepper1989.github.io/miro-board-idea-cards/

For use on a miro board.

you can install with
https://miro.com/oauth/authorize/?response_type=code&client_id=3458764524348786251&redirect_uri=%2Fconfirm-app-install%2F

Documentation is here:
https://developers.miro.com/docs/web-plugins-features

# managing the app
https://miro.com/app/settings/user-profile/apps

# current working test is here:
https://miro.com/app/board/uXjVO43K0e8=/

# Approach(es)
This is a simple example showing different ways of achieving 'Random Quotes' The simplest is text ^ directly here that changes when the modal is opened.

Another approach is shown with the buttons which will pick a random card already on the miro board, bring it to the front and zoom to it

1. First it will look for all cards with the "quote" tag 
1. If it can not find any, it will look for any selected cards
1.  If it can not find any, it will look for any  cards
1.  Finally it will look for any stickers
1.  if nothing is found it will as the user if they want to generate some

I quite like the card quote tag approach as it encourages random choices from user input, but the text above is simpler :)  

# To do
it should be bootstrapped locally following these instructions:
https://developers.miro.com/docs/build-your-first-hello-world-app

Create better version hosted in Code repo

# Watch out / trouble shooting
Every now and then, the plugin seems to stop having "read/write" permisions. When this happens you have to re-install the plugin
