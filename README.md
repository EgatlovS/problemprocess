# problemprocess

Just played around with some exclusive gateways and enums in user-tasks!

## Exclusive Gateway
> An exclusive gateway means exactly one outgoing sequenceflow.
> A converging exclusive gateway means that it doesnt wait for a second token.
> So at the point a token arrives at the gateway it will be send to the outgoing sequence
> flow even if theres for some reason another one out there reaching the gateway in some time.

## Enum
> Theres one thing to say about the enum:
> If you want to reference a chosen value from the enum in another usertask just use
> a string to represent it. I saw a lot of projects do it like this.

***

## bpmn model
![problemprocess](http://i.imgur.com/Rd8X7iT.png)

***

### Stuff used to make this:
 * [camunda modeling reference] (https://camunda.org/bpmn/reference/#gateways-data-based-exclusive-gateways)
 * [camunda docs] (https://docs.camunda.org/manual/7.6/reference/bpmn20/gateways/exclusive-gateway/)
 * [camunda github](https://github.com/camunda/)
 * [camunda modeler](https://camunda.org/download/modeler/)
 * [camunda wildfly distribution](https://camunda.org/download/)

