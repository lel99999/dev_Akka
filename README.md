# dev_Akka
Development of fault-tolerant, concurrent, distributed applications

#### Development System Notes

##### Install sdkman
```
$curl -s "https://get.sdkman.io" | bash
```
Once installed, to run: <br/>
```
$source "$HOME/.sdkman/bin/sdkman-init.sh"
```
** SDKMAN uses the shim design pattern to intercept Java relevant commands and route them to the correct software versions. This design pattern is also used in other version management tools like rbenv (Ruby) and pyenv (Python). **


##### Install scala tools
```
$sdk install sbt
$sdk install scala
```

** List sdk versions:** <br/>
```
$sdk list scala
```
![https://github.com/lel99999/dev_Akka/blob/main/sdk_list_cmd1.png](https://github.com/lel99999/dev_Akka/blob/main/sdk_list_cmd1.png) <br/>

** Change scala versions ** <br/>
```
$sdk use scala 2.11.12
```

