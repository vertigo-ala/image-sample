# image-sample

Sample custom image services local deployment for ALA

The following points are noticeable:

- Australia CAS login
- Bypass CAS security
- Postgres database at jdbc:postgresql://pgdbimage/images (side container)
- Elasticsearch running on a side container
- Commonui runs in a side container (`vertigoala/commonui-sample`) at <http://localhost:8000/commonui-bs3>
- Home at <http://localhost:8080/images/>
- Admin at <http://localhost:8080/images/admin>
- Image-store runs in a nginx container at <http://localhost:8001/store>

Also included are sample files for remote swarm mode deployment.
