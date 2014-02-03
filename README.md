Code for Australia Guides
=============

This repo contains the source files for generating the Code for Australia contribution guides.

Installation
-----------

    gem install guides
    git clone git://github.com/codeforaustralia/guides
		cd guides
		
Run
-----------

		guides preview

Then open `http://localhost:9292` in your web browser

Contributing
-----------

1. Edit the files in the `/source` directory using the textile format
2. Add new chapters to `guides.yml`
2. Commit your changes (`git commit -am "Added new chapter"`)
3. Push to the repo (`git push origin master`)
4. All done!

Issues
-----------

If you are adjusting the layout, be sure to delete the `staging` folder so that it will regenerate on page reload with your changes.