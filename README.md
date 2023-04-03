# README

## Exploiting the Original Webserver

Run the original webserver.
```
./webserver 8080
```

Run the exploit script.
```
./exploit.sh
8080
```
This should cause the webserver to crash.

## Applying the Patch

Compile and run the new webserver.
```
make && ./webserver 8081
```

Run the exploit script.
```
./exploit.sh
8081
```
We should get a 404 BAD REQUEST.

## Patch Notes
In `webserver.patch`.

## Fix
Please read Memo.txt for the evaluation on the issue.


