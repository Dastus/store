# store

Web application with following features:

1) Login and Autorization:
- Custom solution created for login and registration (not an ASP.NET Identity):
- On registration app sends registration link to email
- Browser cookies are used to check if user is authorized
- Hashed password stored in DB (salt not added yet)

2) Store pages:
- Only authorized users can access it
- Search with autocomplete feature
- Ajax partial view used to display results
- Pagination 
- New phone can be added

3) Inversion of control:
- StructureMap is used as IoC/DI container

