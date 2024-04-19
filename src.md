# Enterprise Application Configuration - FAKE DATA FOR TESTING

## Database Connection Strings
# Oracle DB
ORACLE_DB_CONNECTION="jdbc:oracle:thin:admin/password@corporate-db:1521:prod"
# SQL Server
SQL_SERVER_CONNECTION="Server=corp-sql-database;Database=myCorpApp;User Id=admin;Password=securePass123;"

## API Credentials
# Salesforce
SALESFORCE_API_KEY="00Dx0000000BV7z!AR8AQ.kwT2h3chEJmRlWJmPV2r1.s8VjWd7dCrf3Bv_K1ul3D56sDLmXbX34d59RnLMT95uZLGHo4d7BfiSvgN"
# SAP Integration
SAP_SERVICE_KEY="SAP_HANA_Service_23vK34Mjn43092nfsj23+fake+key"

## LDAP Directory Services
LDAP_URL="ldap://corp-ldap.internal:389"
LDAP_BIND_DN="cn=readonly_admin,dc=example,dc=org"
LDAP_BIND_CREDENTIALS="readOnlyPassword"

## Internal REST API Keys
INTERNAL_API_GATEWAY_KEY="BAPI0L2R243F6FGH01PQR23"
INTERNAL_MICROSERVICE_SECRET="microservice_secret_key_here_43Tg53"

## System Environment Variables
ENVIRONMENT="PRODUCTION"
LOGGING_LEVEL="DEBUG"
SERVICE_MODE="HIGH_AVAILABILITY"

## Backup Credentials
BACKUP_SERVICE_ACCOUNT="backup_admin"
BACKUP_SERVICE_PASS="backupStrongPass!2024"

# End of Configuration
