```java
// ~/whoami

import java.util.List;
import java.util.Map;

public class WhoAmI {
    private static final Map<String, Object> ammar = Map.of(
        "role", "software engineer",
        "location", "London",
        "interests", List.of(
            "Distributed Systems",
            "Performance Engineering",
            "AI Infrastructure"
        ),
        "languages", List.of(
            "Python",
            "Java",
            "Go",
            "TypeScript"
        )
    );
}
```
