Usage:
ansible-playbook androidSDK.yml -vvv 2>&1 | tee playbook.log


Roles:

(1) Linux_android-sdk: For installing android SDK on any Linux distribution.
For installing packages, I have used only tar version of packages that makes
this implementation agnostic to Linux distriution.

