# Client Side Architecture

A simple MCV pattern looks like this in modern apps:
* Model: Client Side logic
* View: Client Side View
* Controller: Server Side API

Tasks of the model:
* State management
* Networking & data fetching
* Interaction logic
* Authentication & authorization logic

## Mutation/Query separation
One thing that our architecture should take care of is the mutation/query separation (separate methods that change state from those that don't)

Mutations should not return anything and perform side-effects
Queries should return something and perform no side-effects

## Separation of Concerns
Each layer should handle a separate concern:
* Presentation
* UI Logic
* Container
* Interaction
* Transpor
* Persistence

A feature is a slide of this stack. It goes through every layer (sometimes less)
![Features are vertical slices of the stack](https://khalilstemmler.com/img/blog/client-side-architecture/Frame_50.png)



# Server Side Architecture

We can use the CLEAN model:
* Domain Layer: Contains core domain logic such as entities, value objects and domain events
* Application Layer: Contains application features such as use cases/application services
* Adapter Layer: Contains adapter logic such as access to infrastructure and external APIs
* Infrastructure Layer: Contains infrastructure details such as controllers, routes, database, cache and ORMs