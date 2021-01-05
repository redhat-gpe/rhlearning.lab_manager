# Development Strategy

## Branching Strategy

The branching strategy lays out how we follow the development pathway. This is rather simple, as it follows a simple Feature to Development to Master strategy.

The pathway looks like This

Feature -> Development/Testing -> Master

All changes in feature branches are tested inside of the feature branch, then reviewed and approved by a colleague when merging, to allow for a safe and sanitized developmennt environment. By ensuring the development branch is sanitized before doing pre-production testing, we can ensure that the chance of it being promoted to the mainline branch is at the best possible quality.


Through the use of Molecule, there can be an assurance that all of the Ansible will follow the style requirement and match as required.

## Ansible Standards

The standards laid out in [this example](https://docs.ansible.com/ansible/2.3/playbooks_best_practices.html) from the Ansible docs, best practices guide are the standard for all good Ansible development. By following this information, the Ansible will stay at a high quality, and all the developed code will be standardized between all developed roles/courses, and should be able to pass any sanity checks by molecule with relative ease.

## Molecule

## Testing