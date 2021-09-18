   <body>
    <h1>News-API<h1>
     <h2>Project description</h2>
  <p> The project is a News-API that displays News and enables users to preview news form various sources</p>
     </div>
     </div>
         </ul>
    <h1>Languages and Platforms Used</h1>
    <ul>
    <li>1.Python CLI/Flask to create structure of the News-APP </li>
    <li>2.Python/flask extensions such as-Python_script,NewsAPI </li>
    <li>3.Bookstrap for styling the index page </li>
    </div>
    </div>
    <h1> Authors</h1>
    <p>Andrew Indeche</p>
    <p>Contact indecheandrew@gmail.com</p>
    </div>
    </div>
    <h1>Project Set-up Instructions</h1>
     SetUp / Installation Requirements
Prerequisites
python3.6
pip
virtualenv
Cloning
In your terminal:

  $ git clone https://github.com/emdeechege/NewsApi/
  $ cd NewsPI
Running the Application
Creating the virtual environment

  $ python3.9 -m venv --without-pip virtual
  $ source virtual/bin/env
  $ curl https://bootstrap.pypa.io/get-pip.py | python
Installing Flask and other Modules

  $ python3.6 -m pip install Flask
  $ python3.6 -m pip install Flask-Bootstrap
  $ python3.6 -m pip install Flask-Script
Setting up the API Key

  To be able to gather article info from the News API you will need an API Key.

  * Visit https://newsapi.org/ and register for an API key.
  * In the root directory of the project folder create a file: start.sh
  * Insert the following info into it:

          export NEWS_API_KEY='<Your-Api-Key>'
          python3.6 manage.py server

  * Insert the API Key you received from News Api where <Your-Api-Key> is.
To run the application, in your terminal:

  $ chmod +x start.sh
  $ ./start.sh
Testing the Application
To run the tests for the class files:

  $ python3.6 manage.py tests
     <h1>Bugs</h1>
     <li>Flask_script refusing to open page solution:Activate the virtual form of flask with other packages in the requirements.txt</li>
     </div>
     </div>
      Copyright (c) 2021 Andrew Indeche
   By using and/or copying this project, or the license document from which this statement is linked, you (the licensee) agree that you have read, understood, and will comply with conditions of use.
