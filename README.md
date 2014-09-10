roles
-----

*   support - `git:users`
*   web - `apache:apache`

rights table
------------

    pattern <LWS> owner [ ":" group ] <LWS> oct-mode
    ...

*   pattern:

        ["/"] [<path> "/"] <name> ["/"]

*   owner, group:

        <role>

*   oct-mode:

        3*<oct-digit>
