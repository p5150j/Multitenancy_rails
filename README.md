Multitenancy with Rails
=====================

> Multitenancy with rails. DB per tenant/subdomain 
![enter image description here](https://s3-us-west-2.amazonaws.com/dubhouse/githubImages/tenant.png)
![enter image description here](https://s3-us-west-2.amazonaws.com/dubhouse/githubImages/foo.png)
![enter image description here](https://s3-us-west-2.amazonaws.com/dubhouse/githubImages/yo.png)



```bash
$ git clone [repo]
```

```bash
$ cd Multitenancy_rails
```

```bash
$ bundle
```

```bash
$ rake db:create
```

```bash
$ rake db:migrate
```

```bash
$ rake s
```


```bash
http://lvh.me:3000/users
```

```bash
http://[createdUser].lvh.me:3000/projects
```

```bash
http://[createdUser2].lvh.me:3000/projects
```
