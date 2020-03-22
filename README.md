
<!-- LOGO -->
<br />
<p align="center">
    <img src="https://i.imgur.com/Y8mU04P.png" alt="Logo" height="200">
  <h3 align="center">Organise vaccinations against influenza and whooping cough</h3>
  <h6 align="center">Impfungen gegen Grippe und Keuchhusten organisieren</h6>

  <p align="center">
    #WIRVSVIRUS Corona-Crisis Hackathon - Organized by the German government
    <br />
    <br />
  </p>
</p>

## 🗂 Table of Contents

* [Problem Statement](#-problem-statement)
* [Solution](#-solution)
* [General analysis of the problem](#-general-analysis-of-the-problem)
* [Contact](#-contact)
* [Project Setup](#-project-setup)
* [Contributor](#-contributor)

## 🤯 Problem Statement
> What exact problem are we trying to solve?

The World Health Organization and the Robert Koch Institute
recommend vaccinations against influenza and pertussis (influenza and pneumococcus) to risk groups. The problem is to organise these (with the aim of having as few people as possible in contact with them). In particular, it seems inefficient if each individual person at risk visits a doctor, gets informed about the vaccination, orders vaccine and comes back for vaccination later.

## 🚀 Solution
> How are we trying to solve this problem?

There are different solutions that we try to solve in a web app.
Ideas:  
- Appointment for vaccination online (similar to the appointment with TÜV)
- Information page online cooperation
- Portal for medical assistants and patients

## 📑 General analysis of the problem
> Problems, approaches to solutions, formulation of the challenges, stakeholder group etc.

You can find this in our [Google Document](https://docs.google.com/document/d/1lXkxDYK4uNGaO6yIrNM39e_6-UJcBmuyNB2GVQkAq0s/edit).

## 💌 Contact
> Drop us a line or write with us. Maybe ... help us?

You can write in [Slack](https://wirvsvirus.slack.com/archives/C0103KPLPUK) with us, or in [Discord](https://discord.gg/pVkYShn) (recommended).

## 🔧 Project Setup

> Dependencies:

- Spring Boot Webservices
- Spring Boot Webflux
- Spring Boot MongoDB
- React
    - reactstrap

> Requirements: 

 - Java SDK 1.8.x
 - Node.js
 - NPM
- Maven

1. Clone this Github repo
2. Run the Maven project in your IDE of choice or use

```sh
Linux:
maven clean install

Windows:
mvnw clean install
```

> Frontend

Go into `/src/frontend` and type:
```text
npm i

To start the dev server:
npm start
```


## 👍 Contributor
 > The devs behind the project
 - [Nils Kleinert](https://nilskleinert.de)
 - [Steven Agyekum](https://github.com/Burnett01)
 - [Stephan Tönnies](https://github.com/StephanToennies)
 - [Yannick Radke](https://github.com/YK18415) 

## ❤ Special thanks to
 - [Chris Smith](https://github.com/temar96) ([Helping with the wizards User step-validation](https://github.com/nils-kt/Impfungen-gegen-Grippe-und-Keuchhusten-organisieren/blob/e3732fdd52297230226c1f9e899992339c3035d9/src/frontend/src/components/appointment/steps/UserStep.js#L84))
 - [Josh Piper](https://github.com/JoshPiper) ([Helping with the wizards User step-validation](https://github.com/nils-kt/Impfungen-gegen-Grippe-und-Keuchhusten-organisieren/blob/e3732fdd52297230226c1f9e899992339c3035d9/src/frontend/src/components/appointment/steps/UserStep.js#L84))
