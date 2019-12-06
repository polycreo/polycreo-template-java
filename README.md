# ws2ten1-template-java

## prepare

* your project (ex. `ws2ten1-foobar`)
* your package (ex. `org.ws2ten1.foobar`)

## setup

1. create GitHub repository
2. create Bintray repository
3. clone this repository
4. install ws2ten1/ws2ten1-lint-for-java
5. replace string

    ```
    $ find . -type f -not -path '*/\.*' -not -name 'README.md' | xargs sed -i '' \
            -e 's/@@your-project@@/ws2ten1-foobar/g; s/@@your-package@@/org.ws2ten1.foobar/g'
    ```

6. install gradle wrapper
7. rewrite `./README.md`
8. commit and push
9. configure CircleCI
