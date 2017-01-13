# new-repository

The dependencies I used are the following:


        <neo4j.version>2.3.3</neo4j.version>
        <neo4j.ogm.version>2.0.6</neo4j.ogm.version>
        <ogm.properties>ogm-http.properties</ogm.properties>
   


        <dependencies>
		<dependency>
		<groupId>org.springframework.data</groupId>
        <artifactId>spring-data-neo4j</artifactId>
        <version>4.1.6.RELEASE</version>
		</dependency>
	<dependency>
    		<groupId>org.neo4j</groupId>
    		<artifactId>neo4j</artifactId>
    		<version>2.3.3</version>
	</dependency>


            <dependency>
                <groupId>org.neo4j</groupId>
                <artifactId>neo4j-ogm-core</artifactId>
                <version>${neo4j.ogm.version}</version>
            </dependency>


            <dependency>
                <groupId>org.neo4j</groupId>
                <artifactId>neo4j-ogm-http-driver</artifactId>
                <version>${neo4j.ogm.version}</version>
            </dependency>


            <dependency>
                <groupId>org.springframework.data</groupId>
                <artifactId>spring-data-commons</artifactId>
                <version>1.12.6.RELEASE</version>
            </dependency>

            <dependency>
                <groupId>org.springframework</groupId>
                <artifactId>spring-context</artifactId>
				<version>4.2.9.RELEASE</version>
            </dependency>

            <dependency>
                <groupId>org.springframework</groupId>
                <artifactId>spring-tx</artifactId>
				<version>4.2.9.RELEASE</version>
            </dependency>

            <!-- test-scoped jars -->
            <dependency>
                <groupId>org.springframework</groupId>
                <artifactId>spring-webmvc</artifactId>
                <version>4.2.9.RELEASE</version>
            </dependency>

            <!-- this test dependency also brings in all the drivers -->
            <dependency>
                <groupId>org.neo4j</groupId>
                <artifactId>neo4j-ogm-test</artifactId>
                <version>${neo4j.ogm.version}</version>
                
            </dependency>

            <dependency>
                <groupId>org.neo4j.test</groupId>
                <artifactId>neo4j-harness</artifactId>
                <version>${neo4j.version}</version>
                
            </dependency>

            <!-- jsr 303 tests -->
            <dependency>
                <groupId>org.hibernate</groupId>
                <artifactId>hibernate-validator</artifactId>
                <version>5.3.4.Final</version>
            </dependency>

            <dependency>
                <groupId>org.glassfish</groupId>
                <artifactId>javax.el</artifactId>
                <version>3.0.0</version>
            </dependency>

        </dependencies>

