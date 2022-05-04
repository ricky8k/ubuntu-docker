# ubuntu-docker
Pre-configured Ubuntu Docker image with SSH using [ubuntu-sshd](https://github.com/rastasheep/ubuntu-sshd).

Copied from [ubuntu-template](https://github.com/mogenius/ubuntu-template).

## Deploy
Refer to [ubuntu-sshd](https://github.com/rastasheep/ubuntu-sshd/blob/master/README.md#run-example) for other services.

### Mogenius
- Create a Dockerfile without a template (**Bring your own code**)
- Under repository, use this repo's link under the **Main** branch. 
  - Git: https://github.com/ricky8k/ubuntu-docker.git
- Open port `22` before launching for SSH to the server.
  - TCP, 22, Expose: *True*

## Post-Deployment
- Changing the `root` user's password is **highly recommended** to prevent unauthorized access. To set a new password, use `passwd`.

## Credits
- [rastasheep](https://github.com/rastasheep) for [ubuntu-sshd](https://github.com/rastasheep/ubuntu-sshd)

#
*ricky8k*
- https://github.com/ricky8k
