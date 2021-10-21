# aws-federated-auth

## Description

Script for enumerating and generating profile for AWS federated accounts.

## Example

Display all authorized accounts

```python

aws-federated-auth.py --list

```

Display and generate profiles for all authorized accounts

```python

aws-federated-auth.py

```

Display and generate profiles for specific AWS account

```python

aws-federated-auth.py --account 123456789

```

Display and generate profile for specific AWS account and specifiy session duration

```python

aws-federated-auth.py --duration 1200

```



### Authors/Credits

Crafted with resilience in Philadelphia and/or the Internet November 12, 2019

jdenk@upenn.edu

Based on components of:
    get-aws-creds creds written by batzel@upenn.edu January 10, 2018
