# Terraform Beginner Bootcamp 2023

## Semantic Versioning

This project is uses semantic versioning for its tagging
[server.org](https://semver.org)

MAJOR.MINOR.PATCH  eg. `0.1.1`

## Checking Linux version
```
$ cat /etc/os-release

PRETTY_NAME="Ubuntu 22.04.3 LTS"
NAME="Ubuntu"
VERSION_ID="22.04"
VERSION="22.04.3 LTS (Jammy Jellyfish)"
VERSION_CODENAME=jammy
ID=ubuntu
ID_LIKE=debian
HOME_URL="https://www.ubuntu.com/"
SUPPORT_URL="https://help.ubuntu.com/"
BUG_REPORT_URL="https://bugs.launchpad.net/ubuntu/"
PRIVACY_POLICY_URL="https://www.ubuntu.com/legal/terms-and-policies/privacy-policy"
UBUNTU_CODENAME=jammy
```

## Checking AWS
We can check if aws if configured correctly by running
`aws sts get-caller-identity`

If not configured --> `Unable to locate credentials. You can configure credentials by running "aws configure"`
If successful:
```
{
    "UserId": "EACVXBLU4C2224RXEA34B1",
    "Account": "564342400123",
    "Arn": "arn:aws:iam::564342400123:user/terraform"
}
```