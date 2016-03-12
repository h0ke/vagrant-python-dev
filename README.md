# vagrant-python-dev

An ansible-based vagrant environment for kick-starting server-side python application development with PostgreSQL and Nginx.

## Usage

```
git clone https://github.com/h0ke/vagrant-python-dev.git
cd vagrant-python-dev
vagrant up
```

This will take some time to complete.
Once it's done, you can ssh inside the vm by running `vagrant ssh`

### NOTE

The `ansible-setup-app` role and `synced_folder` are specific to a side project of mine, so feel free to remove/update those to suit your needs.