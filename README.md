# MongoDB

**Original: https://github.com/kubernetes/charts/tree/master/stable/mongodb**

MongoDB is a cross-platform document-oriented database. Classified as a NoSQL database, MongoDB eschews the traditional table-based relational database structure in favor of JSON-like documents with dynamic schemas, making the integration of data in certain types of applications easier and faster.

### Getting start

```
# Add repo to Helm
helm repo add micro-company https://micro-company.github.io/charts/

# Update repo charts
helm repo update

# Install project
helm install --name mongodb micro-company/mongodb
```
