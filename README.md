# auction-service-auth

Handles user registration, login, logout, and password reset.

**Tech:** TypeScript · Express · MySQL · Sequelize · NATS Streaming

## Events Published
- `UserCreated`

## Environment Variables
| Variable | Description |
|---|---|
| `JWT_KEY` | Secret key for signing JWTs |
| `MYSQL_ROOT_PASSWORD` | MySQL root password |
| `AUTH_MYSQL_URI` | MySQL connection URI |
| `NATS_URL` | NATS Streaming server URL |
| `NATS_CLUSTER_ID` | NATS cluster ID |
| `NATS_CLIENT_ID` | Unique client ID (injected by K8s) |

## Local Dev
See [auction-infra](../auction-infra/README.md) for full setup instructions.
