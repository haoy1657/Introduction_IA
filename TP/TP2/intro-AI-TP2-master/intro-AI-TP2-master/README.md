# Intro@AI - TP2

## Setting up your machine

First, update:

```
sudo apt update
```

- **If you work in Ubuntu 18.04:**

If you don't have `pip3`, then:

```shell
sudo apt install python3-pip
```

Then, install `pipenv`:

```shell
pip3 install pipenv
```

(Optional) If you don't have admin privileges, then use this method:

```shell
pip3 install --user pipenv
```

- **If you work in Ubuntu 20.04:**

```shell
sudo apt install pipenv
```

## Inside the directory with the code

Run the following command to syncronize the dependencies needed for the session:

```shell
pipenv sync
```

Then, activate your environment:

```shell
pipenv shell
```

Execute the `jupyter` environment:

```shell
pipenv run jupyter notebook
```

After you finish, shutdown your kernel, quit the `jupyter` environment, and exit the `pipenv` shell:

```shell
exit
```
