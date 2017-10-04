# Ansible Role - mongodb-storage-move

Move a mongodb server storage location to a different directory

Available on Ansible Galaxy: [pgkehle.mongodb-storage-move](https://galaxy.ansible.com/pgkehle/mongodb-storage-move)

# Examples

```YAML
 - hosts: all
   roles:
     - pgkehle.mongodb-storage-move
```

## License

MIT

## Author Information

Paul Kehle  
@pgkehle ([twitter](https://twitter.com/pgkehle), [github](https://github.com/pgkehle), [linkedin](https://www.linkedin.com/in/pgkehle))

## For local development testing

```bash
rsync -av --delete ~/code/ansible-mongodb-storage-move/* ~/.ansible/roles/pgkehle.mongodb-storage-move
```
