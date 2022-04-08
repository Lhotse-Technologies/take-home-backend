# Take-home test Backend


## Overview

This is a takehome test for candidates applying for a backend engineer position at Lhotse.

At lhotse we use Laravel and MySQL, but feel free to use whatever framework, coding style or third-party libraries you think are appropriate.


## Description 
Giving the following `Data Structures`

Requisitions
```
    id: int auto-increment
    reference: uuid
    name: string
    description
    created_at: datetime
    updated_at: datetime
```

Items
```
    id: int auto-increment
    requisition_id: fk int
    reference: uuid
    name: string
    created_at: datetime
    updated_at: datetime
```

### What do you need to do:
1. Create APIs with **CRUD** endpoints for all data structures
2. Add **AUTH** for create/update and delete endpoints
3. You can create a requisition that has multiple items and once a requisition is submitted, it is sent to an email via pdf.
4. Add **Tests** 

