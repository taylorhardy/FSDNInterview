# FSDNInterview
Question 1: The most influential thing I have seen about web development would be a series of articles called Learning and Understanding Angular.js. While I do most of my work in Angular, these articles really instilled all of the possibilities that exist within web applications, and how these possibilities have grown. No longer do we have to write low-level application code to have complex, sharable, data driven application. All of these things are now available to be developed on a web application, if you’re innovative enough. 

Question 2: The largest, and most exciting, application I have built would be an internal DIRECTV application that documented things that happened on an agent's call and provides analytical info graphics for the data that is entered. This tool was built as a way to explain metrics that the business was currently measuring, so instead of being able to say that the agents calls were taking too long we could now provide an answer to why this was happening and generate reports about it. I have learned a great deal from this project, from collaborating with others working on the project to the API of the platform that this web application resides on. We also were taught lessons on database management and user management with this application, in a learn by doing format. My knowledge about Angular.js has greatly expanded, as we have had to solve problems that were encountered along the way. 

Question 3: Here I am taking a list and looping over the list and adding each index to the ouput inside an <li> tag. If this were user input the list would have to grab the data from the html template using a post request. 
def returnStrings():
   listOfStrings = ['here', 'is', 'a', 'list', 'of', 'strings']
   output= '<html><body><ul>'
   for i in range(listOfStrings):
      output += '<li>' + listOfStrings[i] + '</li>'
   output += '</ul> </body></html>'

Question 4: One of the most serious attacks would be SQL injection. With this type of attack the would be attacker is able to inject SQL statements into the URL to perform CRUD operations directly on the database through the client view. Good error handling is a great way to prevent this, as well as creating good database security practices. Another attack is cross-site scripting. By using this the attacker is able to insert JavaScript into the url or inputs on forms. One of the easiest ways to prevent this attack is using input sanitation. 

Question 5:
Here I have two die variables that generate a random number inbetween 1 and 6 then adds up the total. I then use the jsonify method and store the key value pairs using the die and total variables. 

@app.route('/')
def hello_world():
    return 'Hello World!'


@app.route('dice')
def dice_roll():
    die1 = random.randint(1,6)
    die2 = random.randint(1,6)
    roll_total = die1 + die2

    return jsonify(die1=die1, die2=die2, total=roll_total)

if __name__ == '__main__':
    app.debug = True
    app.run()


Question 6: As with any developer with a passion for coding my biggest goal would be to continue learning, especially with the rate of which new frameworks and technologies are being released. However, I do have an eye set on advancing into a management aspect in the developer field, so I want to continue working to increse the skills needed for a roles of that nature.  Strategic and tatical planning, facilitation, and client relationships are some of the areas that I will continue to focus and improve upon.  

