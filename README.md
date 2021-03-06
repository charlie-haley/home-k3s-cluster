# 
<table>
    <tr>
        <th>
            <img src="docs/content/k3s-icon-color.png?raw=true" alt="drawing" width="200"/>
        </th>
        <th>
            <dl>
                <dt><h1>home-k3s-cluster</h3></dt>
                <dd>My personal k3s cluster managed by Flux2 GitOps</dd>
            </dl>
        </th>
    </tr>
</table>




## 💻 Nodes
| Node                     | RAM  | Storage       | Function          | Operating System
| ------------------------ |------| ------------- | ----------------- | -------------------- |
| Raspberry Pi 4 Model B   | 4GB  | 120GB SSD     | Kube Master Node  | Ubuntu 20.10         |
| Raspberry Pi 4 Model B   | 4GB  | 120GB SSD     | Kube Master Node  | Ubuntu 20.10         |
| Raspberry Pi 4 Model B   | 4GB  | 120GB SSD     | Kube Master Node  | Ubuntu 20.10         |
| Raspberry Pi 4 Model B   | 4GB  | 32GB SD       | Kube Worker Node  | Ubuntu 20.10         |
| Raspberry Pi 4 Model B   | 4GB  | 32GB SD       | Kube Worker Node  | Ubuntu 20.10         |
| Dell R210II              | 16GB | 240GB SSD     | Kube Worker Node  | Ubuntu 20.04.2 LTS     |
| HP MicroServer G8        | 8GB  | x4 3TB WD Red | NFS Server        | FreeBSD 12.2-RELEASE   |


## 🦾 Automations
- [Renovate](https://github.com/renovatebot/renovate)
- [GitHub Action YAMLlint](https://github.com/ibiqlik/action-yamllint)
- [Renovate Helm Releases](https://github.com/k8s-at-home/renovate-helm-releases)
- [go-task](https://github.com/go-task/task)
