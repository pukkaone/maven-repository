# Maven Repository

Public Maven repository for projects I maintain


### Configure Your Maven Project To Get Artifacts From This Repository

    <repositories>
      <!-- ... -->

      <repository>
        <id>pukkaone-releases</id>
        <url>https://github.com/pukkaone/maven-repository/raw/master/releases</url>
      </repository>

      <repository>
        <id>pukkaone-snapshots</id>
        <url>https://github.com/pukkaone/maven-repository/raw/master/snapshots</url>
        <releases>
          <enabled>false</enabled>
        </releases>
        <snapshots>
          <enabled>true</enabled>
          <updatePolicy>always</updatePolicy>
        </snapshots>
      </repository>

      <!-- ... -->
    </repositories>
