
## Questions about CP4D 5.0

1. What are the latest features released in cp4d v5.0?
    
    IBM Cloud Pak for Data Version 5.0 includes new features for the platform and for many services. Version 5.0 includes focused end-user experiences for  customers who install multiple solutions on the Cloud Pak for Data control plane, context-aware documentation recommendations, HTTP proxy support, and a standard method for storing and accessing custom certificates. Version 5.0 also includes expanded deployment environment options and the ability to run workloads on remote physical locations.

    This release includes enhancements to existing services, new services, and changes to how services are delivered.

    **New services**
    Data Product Hub enables teams to share governed data assets so that teams can easily access the data that they need.
IBM Knowledge Catalog Standard offers basic governance tooling for cataloging and AI-augmented data enrichment.
IBM Knowledge Catalog Premium includes the full governance framework with data privacy, data quality, cataloging, and enrichment across the data lifecycle with a generative AI layer for enhanced data enrichment.
watsonx Code Assistant for Red Hat® Ansible® Lightspeed helps automation teams create, adopt, and maintain Ansible content more efficiently.
watsonx Code Assistant for Z helps developers modernize their mainframe applications using a combination of automation and generative AI.

    **Renamed services**

    * Db2 Data Gate is now Data Gate
    * Watson Pipelines is now Orchestration Pipelines
    * Watson Query is now Data Virtualization
    
    
2. How to Run Cloud Pak for Data workloads on remote cluster?
    By default, an instance of IBM Cloud Pak for Data runs in a set of projects (namespaces) on a single Red Hat OpenShift® Container Platform cluster. Starting in Cloud Pak for Data Version 5.0, you can expand your Cloud Pak for Data deployment by installing IBM Cloud Pak for Data agents on a remote cluster to create remote physical locations.
After you set up a remote physical location, you can register the physical location with the instance of Cloud Pak for Data that you want to expand. Then, you can add the physical location to a data plane. A data plane is a logical grouping of one or more physical locations. Users can deploy workloads to a data plane. The workload will be scheduled on one of the physical locations associated with the data plane.

4. what are the new features in Cognos Analytics was released in June 2024 with Cloud Pak for Data 5.0.0?
    This release of Cognos Analytics includes the following features and updates:
    Integration with Planning Analytics
    You can now create data server connections to Planning Analytics service instances that are running on Cloud Pak for Data. For details, see Support for     Planning Analytics as a Service in the Cognos Analytics documentation.

    Cognos Analytics uses CA certificates to connect
    You can now use your company's CA certificates on Cloud Pak for Data to validate certificates from your internal servers and connect to Cognos  Analytics. Previously, you had to manually copy the certificates to the artifacts shared volume before you could use them to connect to Cognos Analytics. For details, see Creating a secret to store shared custom certificates.

    Audit logging
    Cognos Analytics now has auditable events that are generated and forwarded by the Audit Logging Service to help you detect and prioritize security threats and data breaches. For details, see Audit events for Cognos Analytics.

    New instance plan size
    Cognos Analytics now has a new plan size, XSmall, which you can select when you create a service instance. For details, see Creating a service instance for Cognos Analytics.

    Updated software version for Cognos Analytics
    The 26.0.0 release of the service provides Version 12.0.3 of the Cognos Analytics software. For details, see Release 12.0.3 - New and changed features in the Cognos Analytics documentation.
    Version 26.0.0 of the Cognos Analytics service includes various fixes.


4. how does the latest features of Data Stage 5.0 compare to Data Stage 4.0 for IBM Cloud Pak for Data 5.0?
    	
    This release of DataStage includes the following features and updates:
    Run DataStage jobs in multiple locations with a remote data plane
    You can now deploy on a remote data plane to run DataStage jobs in multiple locations, including in different geographies or cloud providers, without   creating multipleDataStage instances. For more information, see Deploying on a remote data plane.

     Import and export selected asset typesYou can now select specific asset types to import or export from a .zip file that contains DataStage assets. By default, all asset types are selected.

    Set up metrics storage at the project level for your DataStage flows
    You can now use the metrics repository to store metrics in a database. For more information, see Storing and persisting DataStage metrics.

    Name changes for DataStage connections and connectors
    "Apache Cassandra (optimized)" is now "Apache Cassandra for DataStage."
    "IBM Db2 (optimized") is now "IBM Db2 for DataStage."
    "IBM Netezza Performance Server (optimized)" is now "IBM Netezza Performance Server for DataStage."
    "IBM Watson Query" is now "IBM Data Virtualization."
    "Oracle (optimized)" is now "Oracle Database for DataStage."
    "Salesforce.com (optimized)" is now "Salesforce API for DataStage."
    "Teradata (optimized)" is now "Teradata database for DataStage."
    Your previous settings for the connections, connectors, and their associated jobs remain the same. Only the connection and connector names are changed.

    Connect to more data sources in DataStage
    You can now include data from these data sources in your DataStage flows:
    IBM Planning Analytics
    Microsoft Azure Databricks
    MinIO
    SAP BAPI
    For the full list of connectors, see Supported data sources in DataStage.

    Version 5.0.0 of the DataStage service includes various fixes.

    For details, see What's new and changed in DataStage.

    Related documentation:
    DataStage



[Documentation](https://www.ibm.com/docs/en/cloud-paks/cp-data/5.0.x?topic=overview)
[Quick Start Tutorials](https://www.ibm.com/docs/en/cloud-paks/cp-data/5.0.x?topic=tutorials-quick-start)
