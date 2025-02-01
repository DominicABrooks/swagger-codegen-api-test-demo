# Swagger Codegen API Test Demo

Hey Chop, this is TLDR:

1. **Download the Swagger Codegen JAR** (latest release) from [Maven Repository](https://repo1.maven.org/maven2/io/swagger/swagger-codegen-cli/2.4.44/swagger-codegen-cli-2.4.44.jar).

2. **Generate Python API Test**:

   Run the following command in your terminal:  
   `java -jar {path to swagger-codegen-cli.jar} generate -i {link to swagger json} -l python -o {absolute path to output folder}`

3. **Install Dependencies**:

   Run the following command to install necessary Python packages:  
   `py ./setup.py install`  

4. **Run Unit Tests**:

   Finally, execute the unit tests with:  
   `python -m unittest`
