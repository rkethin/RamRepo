# DuplicateFileFinder
Simple Java command line utility for finding duplicate files. It traverses directories recursively to hunt for duplicate 
files. It first matches by size and then uses a hash off the tail end of the file.

Adding Raj line.

## Building
```java
./gradlew clean shadowJar // To run as jar only
./gradlew clean assembleDist && 
```

## Running Modified
#### Finding Duplicate Files
```java
java -jar build/libs/dupe.jar -p ~/tmp/
```

#### Finding a Specific Duplicate File
```java
java -jar build/libs/dupe.jar -n ~/tmp/test-file -h ~/tmp
```
