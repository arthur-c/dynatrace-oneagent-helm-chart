# dynatrace-oneagent-helm-chart

## Configuration

https://www.dynatrace.com/support/help/infrastructure/containers/how-do-i-deploy-dynatrace-oneagent-on-kubernetes/


| Parameter               | Description                           | Default                                                    |
| ----------------------- | ----------------------------------    | ---------------------------------------------------------- |
| `oneagent_installer_script_url`                  | OneAgent installer script URL with private token               | `{}`                                                   |
|       |   | |

Specify each parameter using the --set key=value[,key=value] argument to helm install.

Alternatively, a YAML file that specifies the values for the parameters can be
provided while installing the chart. For example,

```
$ helm install --name my-release -f values.yaml dynatrace-oneagent
```
