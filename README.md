<a name="readme-top" align="center"></a>

<div align="center">
  <h1>Blog</h1>
  <br/>

</div>

<!-- TABLE OF CONTENTS -->

# 📗 Table of Contents

- [📖 About the Project](#about-project)
  - [🛠 Built With](#built-with)
    - [Tech Stack](#tech-stack)
    - [Key Features](#key-features)
  - [🚀 Live Demo](#live-demo)
- [💻 Getting Started](#getting-started)
  - [Setup](#setup)
  - [Prerequisites](#prerequisites)
  - [Install](#install)
  - [Usage](#usage)
  - [Run tests](#run-tests)
  - [Deployment](#triangular_flag_on_post-deployment)
- [👥 Authors](#authors)
<!-- - [🔭 Future Features](#future-features) -->
- [🤝 Contributing](#contributing)
- [⭐️ Show your support](#support)
- [🙏 Acknowledgements](#acknowledgements)
- [📝 License](#license)

<!-- PROJECT DESCRIPTION -->

# 🏡Blog app <a name="about-project"></a>
Users can create  account and publish articles.

## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

<details>
  <summary>Server</summary>
  <ul>
    <li><a href="https://rubyonrails.org/">Ruby on Rails</a></li>
  </ul>
</details>

<details>
  <summary>Database</summary>
  <ul>
    <li><a href="https://www.postgresql.org/">PostgreSQL</a></li>
  </ul>
</details>

<details>
  <summary>UML Diagram</summary>
  <ul>
    <li>
      <img src="./app/assets/images/entity_relationship_diagram.png" alt="diagram"  height="auto" />
    </li>
 </ul>
</details>



### Key Features <a name="key-features"></a>

 - Rspec Unit testing


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LIVE DEMO -->
## 🚀 Live Demo <a name="live-demo"></a>
[Blog-app](will update soon)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## 💻 Getting Started <a name="getting-started"></a>

To get a local copy up and running, follow these steps.

### Prerequisites
In order to run this project you need:

- To install ruby on your PC. You can read [this](https://rubyinstaller.org/downloads/) documentation on how to do so
- To install postgresql on your PC. You can read [this](https://www.postgresql.org/) documentation on how to do so
- Know how to navigate directories or folders at the CLI.
- Know how to get the URL(https/ssh) of a repository on GitHub.
- You should have a code editor installed, preferably VSCode
- In order to run this project you need:

### Setup
In desired folder or directory in the CLI, run the command:

```sh
git clone git@github.com:asharanjith/asha-blog.git
```

Navigate into the cloned folder or repository by running the command:
```sh
cd asha-blog
```

If VsCode is your default code editor, run:
```sh
code .
```

You are all set up!
### Install

Install this project with:

```sh
 bundle install
``` 
### Usage

To setup the database, run
```sh
rails db:drop db:create db:migrate db:seed
```

 ### Deployment
 
To add the master.key and add key value pair for jwt secret key, follow the following 

1. Please delete config/credentials.yml.enc & config/master.key and run the bellow lin in command prompt
2. Run below command (run only in vs code)
```sh 
    EDITOR=code rails credentials:edit
  ```   
3. Run below command
```sh 
EDITOR="code --wait" bin/rails credentials:edit
```
4. In the new file opened after running the above command, add a key value pair there for jwt
![railssetup](https://github.com/asharanjith/asha-blog/assets/108219288/2b54b86b-69f8-47af-8748-9d9cb730ba35)



 To run the project, execute the following command:
```sh
ruby bin/rails server
```

You can deploy this project using:

```sh
http://[::1]:3000
or
http://127.0.0.1:3000
or
localhost:3000
```  

### Run tests

To run tests, run the following command:

```sh
  rspec spec
```

- The file database.yml is already configured to use those variables

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- AUTHORS -->

## 👥 Authors <a name="authors"></a>
👤  **Asha S Vijayan**

- GitHub: [@asharanjith](https://github.com/asharanjith)
- Twitter: [@asha_cep](https://twitter.com/asha_cep)
- LinkedIn: [asha-vijayan](www.linkedin.com/in/ashavijayan)


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- FUTURE FEATURES -->

## 🔭 Future Features <a name="future-features"></a>

- Messaging system
- Reviews and ratings
- Social media integration such as Facebook, Twitter, and Instagram
- Integration with third-party services such as Google Maps to provide location-based information 

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/asharanjith/asha=blog/issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SUPPORT -->

## ⭐️ Show your support <a name="support"></a>

If you like this project give us a ⭐

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGEMENTS -->

## 🙏 Acknowledgments <a name="acknowledgements"></a>

We would like to thank [udemy](https://udemy.com) for this project inspiration.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## 📝 License <a name="license"></a>

This project is [MIT](./LICENSE) licensed.


<p align="right">(<a href="#readme-top">back to top</a>)</p>
