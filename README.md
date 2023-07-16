# Online Housing Show
Dinger Assessment for Java Backend Developer Intern

# REST API

* `regist owner` `http://localhost:8080/api/auth/register`
* `publicapi(createhousingbyowner)` `http://localhost:8080/api/owner/housing/create`
* `publicapi(updatehousingbyowner)` `http://localhost:8080/api/owner/edit/housing/1/1`
* `public_api(list all housing)` `http://localhost:8080/api/owner/housing/list`
* `public api(list all housing by field name and it value)` `http://localhost:8080/api/owner/housing/list/housingName?val=update`
* `login owner` `http://localhost:8080/api/auth/login`
* `private api (list all housing by owner filter with field with token)` `http://localhost:8080/api/owner/1/housing?createdDate=2023-07-16`
* `private api (get owner and it's housing with token)` `http://localhost:8080/api/owner/1`