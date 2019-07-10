# React Docs

## To create react apps, use package

>\$ npm i -g create-react-app

>create-react-app firstreactapp

>JSX - Javascript Xml

we use babel to compile our jsx code to javascript

## Use Simple react snippet extension by burke holland in VS code

>imr - import react  
>imrc - import react/component  
>cc - class component

## To debug react apps

use chrome extension - React developer tools

## Stateless Functional Components

>SFC cannot have Lifecycle hooks

## Lifecycle Hooks

>Mount - constructor, render, componentDidMount  
>Update - render, componentDidUpdate  
>Unmount - componentWillUnmount  

* constructor - best place to initialize
* componentDidMount - best to make ajax call to display data by setting state
* componentDidUpdate - we can compare prev props and state to decide if we want ajax calls