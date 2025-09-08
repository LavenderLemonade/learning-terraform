readme for the variables example!

long story short, there's different types of them:

- input
    - var<name> 
- local
    - local<name>
    - for local things, like names of services or owner
- output
    - can be used for things we need returned from a teraform config
    - such as getting the ips for databases/EC2 instances so we can connect other things

    types
        - simple
            - string, number, bool
        - complex
            - list, set, map, etc
        - validation
            - type checking is automatic
            - also can use custom config checks

sensitive = true is great for passwords and other things
    - can also pass with an externam sotre, like a secrets manager
    - or can pass with TV_VAR variable, or at runtime