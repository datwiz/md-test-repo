# md-test-repo
repo for testing markdown formatting

Done | build | Docker | Tar | Runtime | Attribute | Config DataType | structure-test type
-- | -- | -- | -- | -- | -- | -- | --
X | X | X | X |   | Cmd | []string | []String
X | X | X | X |   | Entrypoint | []string | []string
X | X | X | X |   | Env | []string | []EnvVar
  | X | X | X |   | OnBuild | []string |  
  | X | _dep ug_ | X |   | Shell | []string |  
  |   | _dep ug_ | nil |   | StopTimeout | *int |  
  | indirect  | X | X |   | ArgsEscaped | bool |  
  |   | empty | empty |   | AttachStderr | bool |  
  |   | empty | empty |   | AttachStdin | bool |  
  |   | empty | empty |   | AttachStdout | bool |  
  |   | false | false |   | NetworkDisabled | bool |  
  |   | X | X |   | OpenStdin | bool |  
  |   | X | X |   | StdinOnce | bool |  
  |   | false | false |   | Tty | bool |  
X |   | X | X |   | Labels | map[string]string | []Label
X |   | X | X |   | ExposedPorts | map[string]struct{} | []string
X |   | X | X |   | Volumes | map[string]struct{} | []string
  |   | empty | empty | X | Domainname | string |  
  |   | empty | empty | X | Hostname | string |  
  |   | sha-hash | sha-hash | <name> | Image | string |  
  |   | empty | empty |   | MacAddress | string |  
  |   | X | X |   | StopSignal | string |  
  |   | X | X |   | User | string |  
X |   | X | X |   | Workdir | string | string
