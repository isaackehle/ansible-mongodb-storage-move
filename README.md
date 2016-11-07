# Ansible: mongodb-storage-move

Ansible role to move a mongodb to a different directory

Available on Ansible Galaxy: [pgkehle.mongodb-storage-move](https://galaxy.ansible.com/pgkehle/mongodb-storage-move)

# Examples

## Example to generate a Certificate Signing Request 

```YAML
 - hosts: all
   roles:
     - pgkehle.mongodb-storage-move
```

This will create a csr in:

- `~/certs/<fqdn>.csr`


## License

MIT

## Author Information

Paul Kehle  
@pgkehle ([twitter](https://twitter.com/pgkehle), [github](https://github.com/pgkehle), [linkedin](https://www.linkedin.com/in/pgkehle))
