Postgresql database is currently available at:

data4dem4lou.cba3kk0t9rmq.us-east-1.rds.amazonaws.com:5432

THIS WILL CHANGE!  This is a temporary aws instance.  Configure flexibly.

Read-Only Access is available:
user:  iheartuser
password:  data4lou

For changes go to @chipmonkey or @thelilacllama for now.

NOTES:  Tables are created from R using RPostgreSQL.
This causes some caveats:
  Table and column names must usually be quoted:  select "Full.Names" from "Legislators";
