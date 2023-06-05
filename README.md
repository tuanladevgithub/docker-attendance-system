# Dockerize for Attendance System project

## Step 1: Clone repositories

```
$ git clone git@github.com:tuanladev98/docker-attendance-system.git
$ cd docker-attendance-system
$ git clone git@github.com:tuanladev98/node-attendance-system-api.git
$ git clone git@github.com:tuanladev98/react-attendance-system-teacher-site.git
$ git clone git@github.com:tuanladev98/react-attendance-system-admin-site.git
$ git clone git@github.com:tuanladev98/react-attendance-system-student-site.git
```

## Step 2: Touch environment file

```
$ cp .env.example .env
```

- Note: change value of environment variables you want to use.

## Step 3: Build

```
$ docker-compose build
$ docker-compose up -d
```
