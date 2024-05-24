# PostgreSQL安装教程

## 安装命令

```shell
sudo apt-get update
sudo apt-get -y install postgresql
```

## 配置密码

> 安装完会在ubuntu-22.04系统上创建一个名字为postgres的用户，因此需要以该用户登录进入操作系统，然后再修改PostgreSQL密码

### 使用账户postgres登录进入系统：

```shell
sudo -i -u postgres
```

### 登录数据库（首次安装时PostgreSQL默认为空）：

```shell
sudo -i -u postgres
```

### 修改用户postgres的密码：

```shell
password postgres
```

### 退出PostgreSQL：

```shell
\q
```