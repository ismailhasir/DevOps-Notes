# More Linux Commands

## User Accounts

- **whoami** \
  matthew

- **id** \
  uid=1001(matthew) gid=1001(matthew) groups=1001(matthew)

- **su** aparna \
  Password:

- **ssh** aparna@192.168.1.2

****

- **ls** /root \
  ⚠ ls: cannot open directory /root: Permission denied

- **sudo ls** /root \
  ✅ anaconda-ks.cfg initial-setup-ks.cfg

## Download Files

- **curl** http://www.some-site.com/some-file.txt -O \
  some-file.txt

- **wget** http://www.some-site.com/some-file.txt -O some-file.txt \
  some-file.txt

## Check OS Version

- **ls** /etc/*release* \
  /etc/centos-release /etc/os-release ***/etc/system-release*** \
  /etc/centos-release-upstream ***/etc/redhead-release*** /etc/system-release-cpe

- **cat** /etc/*release* \
  CentOS Linux release 7.71908(Core) \
  Derived from Red Hat Enterprise Linux 7.7 (Source) \
  NAME="CentOS Linux" \
  VERSION="7 (Core)" \
  ID="centos" \
  ID_LIKE="rhel fedora" \
  VERSION_ID="7" \
  PRETTY_NAME="CentOS Linux 7 (Core)" \
  ANSI_COLOR="0;31" \
  CPE_NAME="cpe:/o:centos:centos:7" \
  HOME_URL="https://ww.centos.org/" \
  BUG_REPORT_URL="https://bugs.centos.org/"
  