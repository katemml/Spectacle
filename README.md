# Spectacle


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)
[![Product Name Screen Shot][product-screenshot2]](https://example.com)


* Designed and implemented a social network web application for users to create and browse posts and support nearby posts search with ReactJS. 
* Launched a scalable web service in Go to handle posts and deployed to Google Cloud.
* Improved the authentication using token based registration/login/logout flow with React Router v4 and server-side user authentication with JWT. 
* Used ElasticSearch (deployed to GCE) to provide search functions 



<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Project Structure
![Product Name Screen Shot][structure]


### Built With
#### Golang, Google Cloud, GAE, GCS, Elastic Search, GCE, Auth, React

<p align="right">(<a href="#readme-top">back to top</a>)</p>




<!-- ROADMAP -->
## Feature Roadmap

- [X] Development Environment Setup
    - [X] Setup GCE instance
    - [X] Create SSH Key for GCE Instance
- [X] Go Handlers
    - [X] Create main.go
    - [X] Create Post Upload Service 
    - [X] Create Signin Handler
    - [X] Create Signin Handler
    - [X] Create  Search Handler
    - [X] Create Delete Handler
    - [X] Create Upload Handler
- [X] Elasticsearch implmentation
    - [X] Install Elasticsearch on GCE Instance
    - [X] Create Elasticsearch Indexes
    - [X] Read Data from Elasticsearch with Go program    
- [X] Front end
    - [X] Install some libraries
    - [X] Update index.js
    - [X] Create constants.js
    - [X] Create Main.js 
    - [X] Create Login.js
    - [X] Create Register.js
    - [X] Create Home.js
    - [X] Create SearchBar.js
    - [X] Configure Router in Main.js
    - [X] Create PhotoGallery.js
    - [X] Create CreatePostButton.js
    - [X] Create PostForm.js   
    - [X] Create corresponding .css  
- [X] GCS
    - [X] Create GCS Bucket
    - [X] Integrate Post Handler with Elasticsearch and GCS      
- [X] Implement Authentication with JSON Web Token(JWT)



<p align="right">(<a href="#readme-top">back to top</a>)</p>




[product-screenshot]: images/screenshot1.png
[product-screenshot2]: images/screenshot2.png

[structure]: images/structure.png



