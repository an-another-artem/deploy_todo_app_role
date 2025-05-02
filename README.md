# Deploy todo app role

### Role installation

#### Requirements file

Add following into your `requirement.yml` file:

```yml
roles:
    - name: an-another-artem.deploy_todo_app_role
```

And install the role with:

```sh
$ ansible-galaxy install -r requirements.yml
```

And use the role in a playbook:

```yml
- name: Test
  hosts: all
  roles:
    - an-another-artem.deploy_todo_app_role

```
