# sql-db-workshop-1.5
A 1.5 hour workshop on Postgres and SQL

## Prerequisites

### Postgres

This is the database we'll be using. Pretty well known around Berkeley, I hear :)

**Installation**: <https://www.postgresql.org/download/> 

**Check**:

```bash
psql --version
# psql (PostgreSQL) 13.2
# (should be at least 12.5 for this workshop)
```

### Platter

Platter makes Postgres branchable, provides a CLI (command line interface) for cloud database instance management, and lets you use a Node/JS connection-less client for leveraging PostgreSQL directly inside Node servers, serverless functions, and even static websites (in alpha on this last target, though). It'll also let us use cloud-hosted Postgres for free during this workshop.

**System reqs**: Linux, or MacOS 10.15+, Intel (Windows in development and installable, but may not be stable/usable by 4/16 hackathon; Mac ARM not yet available)

**Installation**: <https://github.com/boilerplatter/releases>

**Account sign-up**: <https://dashboard.platter.dev/register?cohort=helloworld>

**Check**:

```bash
platter --version
# platter 0.7.2
# should be latest available for this workshop: reinstall on Friday just to make sure.

platter postgres list
# Should first prompt you to log in with the credentials you created above in account sign-up; OK to have an error here after sign-in if you don't yet have any Platter databases, though. See https://docs.platter.dev/cli if you want to explore ahead of time, ignoring all the npm/npx specific parts.
```

Send me an email at <patrick+helloworldworkshop@platter.dev> with the subject **Workshop Participant** and a body including the email associated with your Platter account for freebies and continuing learning resources.
