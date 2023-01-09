### 如何编译和调试?-2023-01-09在JDK8和JDK11下编译通过
```bash
  mvn clean package -D"license.skip=true" -D"jacoco.skip=true" -Dmaven.test.skip=true
```