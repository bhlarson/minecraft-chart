# minecraft-chart
Minecraft kubernetes helm configuraiton

[How to make a Helm chart in 10 minutes](https://opensource.com/article/20/5/helm-charts)

```console
./dr # run minecraft docker container
helm create minecraft-chart
cd ..
helm install minecraft ./helm
```