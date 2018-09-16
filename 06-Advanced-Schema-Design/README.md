

| **URL**             | **CRUD** | **HTTP**    | **SQL**  | **MongoDB**                  | **Mongoose**                  |
| ------------------- | -------- | ----------- |--------- | ---------------------------- | ----------------------------- |
| `/theater/:id`      | `READ`   | `GET`       | `SELECT` |`db.theaters.findOne({ _id: id })`|`Theater.find({ _id: id })`|
| `/theater/new`      | `CREATE` | `POST`      | `ADD`    |`db.theaters.insert(data)`    |`Theater.save()`                |
| `/theater/:id/edit` | `UPDATE` | `POST`      | `UPDATE` |`db.theaters.findOneAndUpdate({ _id: id }, data)`|`Theate.save()`|
| `/theater/:id`      | `DELETE` | `POST`      | `DELETE` |`db.theaters.deleteOne({ _id: id })`|`Theater.deleteOne({ _id: id})`|

