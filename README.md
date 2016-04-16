#Whitewidow
Whitewidow is an open source automated SQL vulnerability scanner, that is capable of running through a file list, or can
scrape Google for potential vulnerable websites

Although whitewidow is completely opensource and free, every now and then even I need a coffee break. If you like this
program and want to help me out with my coffee, donate to my coffee fund

<script
    data-callback="https://github.com/ekultek/whitewidow"
    data-tax="0.00"
    data-shipping="0.00"
    data-amount="1.00"
    data-name="Whitewidow Coffee Break"
    data-button="donate" src="https://www.paypalobjects.com/js/external/paypal-button.min.js?merchant=13aal15b4ck@gmail.com" async="async"
></script>

#Screenshots
![Alt text](http://s30.postimg.org/7ik6ycicx/githubpic.jpg "Credits, legal, TOS")
![Alt text](http://s30.postimg.org/lstr9typd/githubpic2.jpg "Default Mode")
![Alt text](http://s30.postimg.org/5tb3qa2nl/githubpic3.jpg "File Mode")

#Download
Preferably clone repository, alternatively you can download zip and tarball [here](https://github.com/Ekultek/whitewidow/releases/tag/1.0.6)

#Usage
`ruby whitewidow.rb -h` Will print the help page

`ruby whitewidow.rb -e` Will print the examples page

`ruby whitewidow.rb -f <path/to/file>` Will run Whitewidow through a file, you will not need to provide whitewidow the
full path to the file, just provide it the paths within the whitewidow directory itself. Also you will not need a beginning
slash, example:

    - whitewidow.rb -f tmp/sites.txt #<= CORRECT
    - whitewidow.rb -f /home/users/me/whitewidow-1.0.6/tmp/sites.txt #<= INCORRECT

`ruby whitewidow.rb -d` Will run whitewidow in default mode and scrape Google using the search queries in the lib directory

#Dependencies
`gem 'mechanize'`

`gem 'nokogiri', '~> 1.6.7.2'`

`gem 'rest-client'`

`gem 'colored'`

To install all gem dependencies, follow the following template:

`cd whitewidow`

`bundle install`

This should install all gems needed, and will allow you to run the program without trouble.

#Misc
Being an open source project, feel free to contribute your ideas and open pull request. You can fork it clone it do pretty
much whatever you want to do with it. For more information including copyright info please see the docs.

If you decide
to contribute to this project, your name will go in the docs under the author and credits file. It will remain there to
show that you have successfully contributed to Whitewidow. Thank you ahead of time for all contributions

Current Version 1.0.6
