boilerplate
===========

Rails factory boilerplate including: 
*factorygirl
*shoulda
*mocha
*capybara
*cucumber

Branches are planned for various authorization boilerplates:

* Devise
* Omniauth
* Devise + Omniauth

Important Security Notes

* Make sure to regenerate your secret with rake secret after forking!
* If your fork will be open source, be sure to add config/initializers/secret_token.rb to your .gitignore!
* Set the FACEBOOK_KEY and FACEBOOK_SECRET environment variables in application.rb (for development, test) and production.rb (production) and add those files to .gitignore to avoid disclosing your credentials in an open-source repo.