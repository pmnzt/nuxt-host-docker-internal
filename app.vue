<template>
  <div>
    Call POST http://localhost:3000/api/team/admin 
    add simple body
    <br />
    Example:
    <code>curl -X POST -H "Content-Type: application/json" -d '{"name": "John"}' http://localhost:3000/api/team/admin</code>

    Works right?
    <br />

    Now try calling this from docker.
    Example:
    <br />
    http://host.docker.internal:3000/api/team/admin

    <br />

    Does it work for ya?
  </div>
</template>
