	___________________________________________________________________
	||     *                            *                    ((   *  ||
	||        *                 *                *            ~      ||
	||                ___.                          *          *     ||
	||       *    ___.\__|.__.           *                           ||
	||            \__|. .| \_|.                                      ||
	||            . X|___|___| .                         *           ||
	||          .__/_||____ ||__.            *                /\     ||
	||  *     .  |/|____ |_\|_ |/ _                          /  \    ||
	||        \ _/ |_X__\|_  |\||~,~{                       /    \   ||
	||         \/\ |/|    |_ |/:|`X'{                   _ _/      \__||
	||          \ \/ |___ |_\|_.|~~~                   /    . .. . ..||
	||         _|X/\ |___\|_ :| |_.                  - .......... . .||
	||         | __\_:____ |  ||o-|            ___/........ . . .. ..||
	||         |/_-|-_|__ \|_ |/--|       ____/  . . .. . . .. ... . ||
	|| ........:| -|- o-o\_:_\|o-/:....../...........................||
	|| ._._._._._\=\====o==o==o=/:.._._._._._._._._._._._._._._._._._||
	|| _._._._._._\_\ ._._._._.:._._._._._._._._._._._._._.P_._._._._||
	|| ._._._._._._._._._._._._._._._._._._._._._._._._._._._._._._._||
	||---------------------------------------------------------------||
	                                                -Manoj Jain



#SAILS

***** 

###WELCOME TO SAILS

take everything you think about javascript and imagine putting it in a box. now take that imaginary-javascript-mind-box, and throw it out the window. that's right, defenistrate that goddamn box. imagine that box falling seventy-three stories to its inevitable annihilation. 

good. glad we got that out of the way.

sails is very similar to its homophone counterpart, rails, in that it works on the MVC premise. it's a lightweight, enterprise-grade (whatever that means) web framework to build super cool web apps on. it also loads really cool ascii art in your terminal.

###GETTING STARTED

1. to initiate a ~~rails~~ sails app, first download the framework by typing ```npm install sails -g``` in the terminal.

2. then type ```sails new FOLDERNAME``` into the terminal. (seriously, don't type foldername. why do people always take these tutorials so literally?)

3. sails is like one of those rich parents that raised the stereotypical rich millenial. it's gonna do pretty much all your work for you. so when it creates the folder, open it up in sublime text and take a look at how pampered you are. take a moment to appreciate that. take a minute to check your privilege. no, seriously, sails is going to make your assets folder, your public folder, your config folder, your basic routes, a whole slew of useful modules, and your api folder for you. take a minute to actually click through things.

4. since we're only doing a little hello world app for now, head over to **config → routes** and make a route for the homepage. the routes file in sails takes routes as hashes; so write your route as a string followed by a colon, and then inside of your route hash, write view with a colon and then the view you want to route to rely on as a string. since we're going to the homepage, we're going to use *index* as the view.

``` &quot;\\&quot;: {   
	view: &quot;index&quot;   
}   
```

(note: you could just copy and paste all this code piece by piece and make it work but please try to write it out. if you want to have any hope of existing in the digital age, you're going to need to be able to type at more than 20WPM, so practice makes perfect!)

5. now that you've got your route set up, head over to **config → views** and make an index.ejs. 


now type ```sails generate api user``` in the 