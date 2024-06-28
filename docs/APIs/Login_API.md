# Login API

## Create Admin

### EndPoint: zeroumcompany.com/user/create_admin/

### Testes:
- <span style="color: red;"> 201 - Created</span>
- <span style="color: red;"> 401 - Unathorized</span>
- <span style="color: green;"> 406 - Role must be admin</span>

## Create Supervisor

### EndPoint: zeroumcompany.com/user/create_supervisor/

### Testes:
- <span style="color: red;"> 201 - Created</span>
- <span style="color: red;"> 401 - Unathorized</span>
- <span style="color: green;"> 406 - Role must be admin</span>

## Create Colaborador

### EndPoint: zeroumcompany.com/user/create_colaborador/

### Testes:
- <span style="color: red;"> 201 - Created</span>
- <span style="color: red;"> 401 - Unathorized</span>
- <span style="color: green;"> 406 - Role must be supervisor or admin</span>

