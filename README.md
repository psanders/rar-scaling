# RAR-SCALING

This stack features the basic components needed to scale Asterisk. It uses [Routr I/O](https://github.com/fonoster/routr) as the SIP Server and RTPEngine for media relay.

## Requirements

- Docker and Docker Compose
- Git (optional)

## Setting the conditions

➊ Download the project

```bash
git clone https://github.com/psanders/rar-scaling
```

➋  Update the variable `EXTERN_ADDR` at `.env` to reflect your enviroment. 

## Running the stack

Run the stack with the following command:

```bash
docker-compose up
```
