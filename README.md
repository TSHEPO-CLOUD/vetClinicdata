# vetClinicdata

## Table of Contents

- [About Project](#about-project)
- [Built With](#built-with)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [Author](#author)
- [Acknowledgements](#acknowledgements)
- [Show your support](#show-your-support)

## About Project

This project is built as a practice for optimizing search queries in a populated database. We start with a regular database, then fill it with data to slow down the query times, and then use optimization techniques to achieve faster query calls compared to the unoptimized ones. Using this project, you can replicate the database to see how you can also implement your own solutions to the problems, or see how your solution compares to ours.

The following are screenshot displaying the before and after results on analysing the SQL data.
### BEFORE

![query_one_before](./assets/QueryBefore.png)

### AFTER

![query_one_after](./assets/QueryAfter.png)

## Built With

- PostgreSQL

## Prerequisites

- Ensure you have PostgreSQL DBMS installed

```bash
sudo apt update && sudo apt install postgresql postgresql-contrib
```

## Getting Started

- Clone this repo <https://github.com/TSHEPO-CLOUD/vetClinicdata.git>

  ```bash
  git clone https://github.com/TSHEPO-CLOUD/vetClinicdata.git
  ```

- Navigate to vetClinicdata folder/directory

  ```bash
  cd vetClinicdata
  ```

- Create the `vetClinicdata` database

- If you need help working with Postgres follow this **_[GUIDE](https://www.digitalocean.com/community/tutorials/how-to-install-postgresql-on-ubuntu-20-04-quickstart)_**

- **Creating Tables**

```bash
psql vetClinicdata < schema.sql
```

- **Add data to Tables**

```bash
psql vetClinicdata < data.sql
```

- **Run the Queries**

```bash
psql vetClinicdata < queries.sql
```

## Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/TSHEPO-CLOUD/vetClinicdata/issues)

1. Fork the Project
2. Create your Feature Branch (`git checkout -b Feature-b`)
3. Commit your Changes (`git commit -m 'Add some Feature-b'`)
4. Push to the Branch (`git push -u origin Feature-b`)
5. Open a Pull Request

## Authors



👤 **Shonibare Adewunmi Comfort**
- GitHub: [@Adewunmi97](https://github.com/Adewunmi97)
- Twitter: [@ShonibareC](https://twitter.com/ShonibareC)
- Linkedin: [Adewunmi Shonibare](https://www.linkedin.com/in/adewunmi97)

👤 **Tshepo David**

- GitHub: [@githubhandle](https://github.com/TSHEPO-CLOUD)
- Twitter: [Twetter](https://twitter.com/tshepomolefem)
- Linkedin: [Linkedin](https://www.linkedin.com/in/tshepo-molefe-8153313b)


## Acknowledgements

- [Postgres ORG](https://www.postgresql.org/) for the documentation and guides on getting started with PostgreSQL DBMS.

## Show your support

Give a ⭐️ if you like this project!