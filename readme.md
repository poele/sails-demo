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

Take everything you think you know about JavaScript, and imagine putting it in a box. Now take that imaginary-JavaScript-mind-box, and throw it out the window. That's right, defenistrate that goddamn box. Imagine that box falling seventy-three stories to its inevitable annihilation. 

Good. Glad we got that out of the way.

Sails is very similar to its homophone counterpart, rails, in that it works on the MVC premise. It's a lightweight, enterprise-grade (whatever that means) web framework to build super cool web apps on. It also loads really cool ascii art in your terminal.

###GETTING STARTED

1. To initiate a ~~rails~~ sails app, first download the framework by typing ```npm install sails -g``` in the terminal.

2. Then type ```sails new FOLDERNAME``` into the terminal (seriously, don't type foldername. Why do people always take these tutorials so literally?).

3. Sails is like one of those rich parents that raised the stereotypical rich millenial. It's gonna do pretty much all of your work for you. So when it creates the folder, open it up in sublime text and take a look at how pampered you are. Take a moment to appreciate that. Take a minute to check your privilege. No, seriously, sails is going to make your assets folder, your public folder, your config folder, your basic routes, a whole slew of useful modules, and your api folder for you. Take a minute to actually click through things.

4. Since we're only doing a little hello world app for now, head over to **config → routes** and make a route for the homepage. The routes file in sails takes routes as hashes; so write your route as a string followed by a colon, and then inside of your route hash, write view with a colon and then the view you want to route to rely on as a string. Since we're going to the homepage, we're going to use *index* as the view.

```  
"\": {   
	view: "index"
}   
```

(note: you could just copy and paste all this code piece by piece and make it work but please try to write it out. If you want to have any hope of existing in the digital age, you're going to need to be able to type at more than 20WPM, so practice makes perfect!)

5. Now that you've got your route set up, head over to **config → views** and make an index.ejs. Since sails runs on JavaScript, it automatically defaults to ejs files for templating, although you can specify a different templating library if you want. I guess. Anyway, inside your index.ejs file, type... oh seriously. you can format hello world in a header tag by your damn self.

6. Okay, ready? Hope you've been saving or this'll have all been for naught. Type ```sails lift``` in your console. Visit http://localhost:1337 (because this is for leet programmers ONLY) to visit your homepage. Welcome to the world of sails!