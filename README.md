System requirements
Java 17 or higher installed.
Spring Boot 3.3.x or higher

configure the jar of the server in claude configuration file.
{
  "mcpServers": {
    "spring-ai-mcp-weather": {
      "command": "java",
      "args": [
        "-Dspring.ai.mcp.server.stdio=true",
        "-jar",
        "/ABSOLUTE/PATH/TO/PARENT/FOLDER/mcp-weather-stdio-server-0.0.1-SNAPSHOT.jar"
      ]
    }
  }
}
A sample of the configuration is attached here under resources folder.

Save the file and restart claude desktop.
