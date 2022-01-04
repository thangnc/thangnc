```java

package thangnc;

import java.util.Arrays;
import java.util.HashMap;
import java.util.List;
import java.util.Map;

public class AboutMe {
    public Map<String, String> getCurrentWorkplace() {
        Map<String, String> currentWorkplace = new HashMap<>();
        currentWorkplace.put("company", "Est Rouge United");

        return currentWorkplace;
    }

    public Map<String, List<String>> getTechnologies() {
        Map<String, List<String>> techs = new HashMap<>();
        techs.put("back-end", Arrays.asList("Java", "NodeJS", "Python"));
        techs.put("front-end", Arrays.asList("Angular", "VueJS"));
        techs.put("mobile", Arrays.asList("Android", "Flutter"));
        techs.put("test", Arrays.asList("JUnit", "Selenium", "Gatling"));
        techs.put("databases", Arrays.asList("MySQL", "MongoDB", "SQLite", "Presto"));
        techs.put("devops", Arrays.asList("AWS", "Ansible", "Docker", "Jenkins", "CircleCI", "TravisCI", "Hashicorp Vault", "Datadog", "Sentry", "EFK", "ELK"));
        techs.put("os", Arrays.asList("Linux", "MacOS"));

        return techs;
    }
}
```
