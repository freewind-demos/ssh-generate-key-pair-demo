SSH Generate Key Pair Demo

https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

1. RSA
------

```
ssh-keygen -t rsa -b 4096 -C "freewindlee@gmail.com"
```

2. ed25519

```
ssh-keygen -t ed25519 -C "freewindlee@example.com"
```