|version| 0.1.0| [MIT license](LICENSE)|Copyright (c) 2021 Bart Lievers|[blog](https://vblog.bartlievers.nl)|[github](https://github.com/brtlvrs/)|[dockerhub](https://hub.docker.com/u/brtlvrs)|
|---|---|---|---|---|---|---|

# Ansible playbooks for provnode

This folder contains the ansible playbooks to run on the provnode.
The following files are ignored in the repository.<br>
They have template files ending on .tmpl 

|File|Reason|Comment|
|---|---|---|
|inventory.yaml| Contains sensitve connection information| inventory.yaml.tmpl is the template file<br> to be used for creating this file.
|.vault-pass.txt| Contains the encryption key used for Ansible-vault|