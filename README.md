# firedog-lemp
You can run firedog bot at kubernetes.

## Configuration
Secret file

```yaml
apiVersion: v1
kind: Secret
metadata:
  name: bot-secret
type: Opaque
data:
  token: (base64 discord token)
  db-port: (base64 mysql port)
  db-host: (base64 mysql host)
  db-user: (base64 mysql user)
  db-password: (base64 mysql password)
  db-name: (base64 mysql database name)
```
