# MIMUW JNP-2 Task-1

While booted every file dropped into the 'magic_folder' is sent
by email (as text not attachment), the same file is moved to
'visible' folder, then copied and zipped to 'zip_out' folder, every
file in visible folder can be accessed using:

```
http://localhost:8087/showFile/{file_name}.
```

# Building:
```
gradle build
```

# Running:
```
gradle bootRun
```

Used components:

## Mail:
https://camel.apache.org/components/latest/mail-component.html

## File:
https://camel.apache.org/components/latest/file-component.html

## Rest:
https://camel.apache.org/components/3.7.x/rest-component.html
