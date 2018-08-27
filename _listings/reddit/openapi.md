swagger: "2.0"
x-collection-name: Reddit
x-complete: 1
info:
  title: Reddit
  version: 1.0.0
host: www.reddit.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /mute_message_author:
    post&nbsp;:
      summary: Add Mute Message Author
      description: For muting user via modmail.
      operationId: post&nbsp;MuteMessageAuthor
      x-api-path-slug: mute-message-author-postnbsp
      parameters:
      - in: query
        name: id
        description: fullname of a thing
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Mute
      - Message
      - Author
  /unmute_message_author:
    post&nbsp;:
      summary: Add Unmute Message Author
      description: For unmuting user via modmail.
      operationId: post&nbsp;UnmuteMessageAuthor
      x-api-path-slug: unmute-message-author-postnbsp
      parameters:
      - in: query
        name: id
        description: fullname of a thing
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Unmute
      - Message
      - Author