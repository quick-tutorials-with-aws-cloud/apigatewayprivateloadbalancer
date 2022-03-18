# apigatewayprivateloadbalancer

This project creates:
- A Private REST API Gateway;
    - Endpoints enabled:
        - GET /customers;
        - POST /customers;
        - GET /customers/{id};
        - PUT /customers/{id};
        - DELETE /customers/{id};
- An integration between an API and a Network Load Balancer;

## Helpful links

- [What is Amazon API Gateway?][1]
- [Working with REST APIs][2]
- [What is a Network Load Balancer?][3]

[1]: https://docs.aws.amazon.com/apigateway/latest/developerguide/welcome.html
[2]: https://docs.aws.amazon.com/apigateway/latest/developerguide/apigateway-rest-api.html
[3]: https://docs.aws.amazon.com/elasticloadbalancing/latest/network/introduction.html