## dpd-importer

Create deployd collections from existing mysql tables.

### about

This is a **deployd module** that allows you to import existing mysql tables into an existing or new deployd project. The impoter will pull in all existing data and use it to built your deployd collection's schema.

### usage

Create a project. Then install the dpd-importer module.

    dpd create my-app
    cd my-app
    mkdir node_modules
    npm install dpd-mysql-importer
    dpd -d
    
Click the green new resource and choose **Importer**.

Give it the default name "/importersql". Open it by clicking "IMPORTER" in the left menu.

Enter the information of your existing Mysql server. Clicking on **Start Import** will start creating deployd collections from data in the provided db by streaming data directly from the old db into your new deployd db.

### use with caution

This is alpha software. Please use with caution and report any issues or feature requests.

