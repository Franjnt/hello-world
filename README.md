<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NPM Clone</title>
    <link rel="stylesheet" href="./style.css" />
</head>

<head>

  </head>

<body>
    <header>
        <div>
            <div>
                <img class="blackHeart" src="./images/black-heart.png" alt="black heart" />
                <span> Nifty Penguin Magic </span>
            </div>
            <nav>
                <ul>
                    <li><a href="#"> npm Enterprise </a></li>
                    <li><a href="#"> Products </a></li>
                    <li><a href="#"> Solutions </a></li>
                    <li><a href="#"> Resources </a></li>
                    <li><a href="#"> Docs </a></li>
                    <li><a href="#"> Support </a></li>
                </ul>
            </nav>
        </div>
    
        <div>
            <div>
                <img class="blackHeart" src="./images/npm-logo.png" alt="logo" />
            </div>
            <div>
                <img class="blackHeart" src="./images/magnifying-glass.png" alt="glass" />
            </div>
            <div class="bar">
                <input type="text" placeholder="Search packages">
                <button>Search</button>
                <a href="#">Join</a>
                <a href="#">Log In</a>
                
                
            </div>
        </div>
    </header>
    
    <section class="presentation">
        <h1 class= build>
            Build amazing things
        </h1>
        <article class="essential">
            Essential JavaScript development tools that help you go to market faster and build powerful applications using
            modern open source code.
        </article>
        <div class="submit">
            <a href="#" style="color: white;">See plans</a> 
            <a href="#" style="background-color: white; color:black">Join for free</a>
          
        <h1 class="bring">
    Bring the best of open source to your company
        </h1>
        <article class="npm">
    npm is the tool used by
over 11,000,000 JavaScript developers around the world. Your developers already use it. Your company depends on it.
Create an Org and get more out of the tools your team already knows and loves.
        </article>
    </section>
    
    <section class="pie">
        <div>
            <img src="" alt="">
            <h4>Zero configuration</h4>
            <p class="create">Create an org, add
your team, and start collaborating.<br> Nothing to configure, set up, or manage.</p>
        </div>
        <div>
            <img src="" alt="">
            <h4>Team management</h4>
            <p class="create">Control who has access to
what modules within your team namespace using straightforward team management capabilities.</p>
        </div>
        <div>
            <img src="./images/" alt="">
            <h4>Familiar features</h4>
            <p class="create">npm Orgs
has 100% parity with all the public npm registry features your developers already use.</p>
        </div>
        <div>
            <img src="" alt="">
            <h4>npm audit</h4>
            <p class="create">Enjoy the security
auditing features built into the npm client, a zero-friction way to make open source software safer. Create an Org</p>
        </div>
        <a href="#" style="width: 8px, 8px, 0; color: green">Create an Org</a>
    </section>
</body>
</html>






//archivo css

@import url('https://fonts.googleapis.com/css?family=Poppins');

body {
  font-family: 'Poppins';
}

header > div {
    padding: 0 25px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-bottom: 1px solid lightgray;
  }
  
  nav {
    width: 600px;
  }
  
  nav ul {
    list-style: none;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  
  nav a {
    text-decoration: none;
    color: black;
  }
  
  .blackHeart {
    width: 20px;
    margin-right: 1rem;
  }

  div > input  {
    width: 900px;
    height: 30px;
    padding-left: 50px;
  
  }

    button {
      height: 30px;
      color: white;
      background-color: #fb3e44;
    }
     


    .presentation {
      height: 600px;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      background-color: rgba (232,217,217,3);
    }

    
    .essential {
      text-align: center;
      width: 415px;
      margin-right: 100px;
      margin-left: 100px;
    }

    .submit {
      background-color: #FB3B49;
      padding: 30px;
      margin: 20px;
      margin-left: 550px;
      margin-right: 550px;
      height: 20px;
      color: white;
      text-align: center;
    }

    .sub {
      flex-direction: row;
      color: green;
    }

    
    
    }
    
    .bring {
      color: black;
      background-color: rgba(255,204,53,4);
      transform: skew(9deg,0deg);
      font-style: italic;
      margin-right: 100px;
      margin-left: 100px;
      text-align: center;
    }

    .npm {
      text-align: center;
      margin-right: 105px;
      margin-left: 105px;
      justify-content: center;

    }

    .zero {
      color: red;
    }

    .pie {
      flex-direction: row;
      text-align: left;
      justify-content: left;
      color: #ED1C24;
      width: 300px;
    }

    .create {
      flex-direction: row;
      color: black;
      padding: 20px;

    }

   
    }
}

}
