# Home Works DevOps

## HW №16. Docker and Docker-compose

- Build images fronted and backend
- Build and push images to DockerHub
- Run containers
- `docker compose up -d` Use docker-compose from file
- Let's make it possible to work with the use of ENV vars in order to define your API URL on the backend service
- Rebuild the environment `docker compose up --build -d`

## HW №17. Docker Swarm (work inside folder hw_16)

- Create docker-compose.stack.yml
- Init Swarm Mode `docker swarm init`
- Use main and auxiliary config `docker stack deploy -c docker-compose.yml -c docker-compose.stack.yml realworld`

## HW №18. AWS cli

- Create keys for using with SSH connections to EC2 instances
Create custom VPC with one public subnet with Internet connectivity `awscli-1.txt`
- Create custom VPC with one public and one private subnet, both must have an Internet connectivity `awscli-2.txt`

## HW №19. Terraform

- Create AWS VPC, public and private subnets, Internet Gateway, security groups with use terraform code
- Use command:
              `terraform init`
              `terraform plan`
              `terraform apply`
              `terraform destroy`

## HW №20. Terraform modules

- Create project with object AWS infrastructure:
- VPC, private, public subnets, security-group, two ec2 instance

## HW №21. Ansible: Intro

- Python Virtual Env
- Ansible
- Ad-hoc commands
- Dynamic Inventory
- Ansible Playbook
- Use this on AWS infrastructure with terraform code
`python3 -m pipenv shell`
`pipenv sync`
`ansible-playbook --limit tag_Project_realworld playbook.yml`

## HW №22. Ansible: Vault, Handlers, Vagrant, Templates

- Ansible vault, handlers, templates
- Vagrant provisioner in ansible
- Ansible tags
- Ansible lint

## HW №23. Ansible: Roles, Molecule

- Create ansible role
- Work check on VM vagrant with virtualbox
- Edit playbook for roles
- Testing role with molecule `molecule test` 




