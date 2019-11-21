# Resume generator
Resume generator is a project that is focused on generating a resume with a lot of features

  - You can fill in your details like filling a form
  - You can choose a theme that you want for your resume
  - Magically the resume will be generated and will be sent to your email and can be shared with others by getting a link that can be made public or private and can also be downloaded offline

# Other Features
You can also:
  - There will be a microservice for generating resumes that can be used by third party apps like Linkedin etc
  - This is completetly open source 
  - This project will go into production and everything will be moved to cloud (AWS/Google) and can be scaled upto thousands of users


# Why should I Contribute ??
> Currently there is no open source resume generators that are free once this is devloped and deployed anyone can use it at a free cost

### Tech

 Uses a number of open source projects to work properly:

* [ReactJS/Svelte/Vue] - HTML enhanced for web apps!
* [TailWind CSS] - great UI boilerplate for modern web apps (https://tailwindcss.com/)
* [Node.js with TypeScript] - evented I/O for the backend
* [Express] - NestJS framework (https://nestjs.com/) 
* [Gulp] - the streaming build system
* [Cypress] - A frontend testing library (https://www.cypress.io/)
* [AWS Cloud functions] - Some Cloud functions that serve the purpose of generating resume and sending it via email
* [MongoDB] - Used to store details of the user for editing in future 

And of course this project itself is open source with a [public repository][https://github.com/mark-nakachon/Resume-generator]
 on GitHub.

### Development

Want to contribute? Great!

Anyone who are trying to start their open source journey can contribute to this project.

You guys can generate issues and also raise Pull Requests for this repository you are welcome

### Deployment

The frontend for this project will be deployed on AWS S3 buckets using Cloud Front as a CDN

The backend for this project will be deployed using Docker on Google Cloud Run (https://cloud.google.com/run/)

### Docker

It is better guys if you start running all these services in a docker container using (docker-compose)

### Todos
 - Write MORE Code
 - Write MORE Tests
 - Add Night Mode
 - Raise PR's

License
----

MIT


