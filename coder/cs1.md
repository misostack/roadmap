# CS1

## Headfirst

- NodeJS -> ExpressJS : Auth Module, Users CRUD, Project CRUD, Tasks CRUD, SpendTime CRUD, File CRUD, SocketIO, S3
- Angular : Auth Module, Users CRUD, Project CRUD, TasksCRUD, SpendTime CRUD, File CRUD, MarkDown2HTML,
- ReactJS : Auth Module, Users CRUD, Project CRUD, TasksCRUD, SpendTime CRUD, FIle CRUD, MarkDown2HTML, Redux & ReduxForm

**Build an application with the following features:**

- Auth Module : login, register, reset-password
- User Module: edit profile, user/change-password, user/change-email
- CRUD Users
- CRUD Menu
- CRUD Menu items
- CRUD Dataset : stores, districts, ... 
- File Module : upload file to S3

> Local CI&CD : https://about.gitlab.com/install/#ubuntu 
> Pipelines : Heroku 
> Host: Heroku 
> Git: github.com 
> CI & CD: gitlab

##  NodeJS - Express - WebService

- Build the monolith architecture
- REST API prototype
- DDD: entities, value objects, services, repository, factory
 

## JS - ReactJS

- Build a component based structure with Redux
- Web Application

## Typescript - Angular

- Build a component based structure
- Router -> Container -> Presentation
- Presentation -> Dispatch Data, User's action -> Container
- Container -> StateService -> Service -> API
- API -> Service -> StateService -> Container -> Presentation
- State Management : Service + Resolve + Observable

> Eg:
> AppStateResolver => appState$
> appState$.subscribe(states => console.log(states))
> appStateService.dispatch({action: CREATE_TASK, payload: {...data}})
> actions: CREATE|READ|UPDATE|DELETE + _ + 'ENTITY'
> custom_actions: DO_LOGIN, DO_LOGOUT

