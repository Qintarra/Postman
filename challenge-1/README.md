## Postman

### Copmosing a request

Retrieve the second page of tickets for a board with 2 items per page.

The URL for ticketson a board is http://localhost:3000/api/boards/{{BOARD_ID}}/tickets

1. Replace {{BOARD_ID}} with an ID from the board list.
2. Restrict the returned list to only 2 items using the **ps** query string parameter.
3. Specify the second page of resultswith the **pn** query string parameter.
***Note that the page number is 0 based, so the first page is zero.***
4. Set the 'User Agent' header to 'LinkedIn/Postman'before sending the request.
