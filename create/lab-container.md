## Getting Started

In this lab, you will create an Azure Cosmos DB container.

### Create Azure Cosmos DB Resource

> You will use the Azure Cosmos DB account to created in the previous lab.

1. On the left side of the portal, click the **All services** link.

1. At the top of the **New** blade, locate the **Search Everything** field.

1. Enter the text **Cosmos** into the search field and press **Enter**.

1. In the **Everything** search results blade, select the **Azure Cosmos DB** result.

1. In the **Azure Cosmos DB** blade, click the Cosmos DB account.

1. In the new **Azure Cosmos DB Account** blade, perform the following actions:

    1. Click on **Overview** on the left hand side.

    1. Click on **Add Container**.
    
    1. In the **Database id** section, enter the value **trainingdb** into the field.
    
    1. Check **Provision database throughput**
    
    1. Set the **Throughput** to **400**
    
    1. Enter **trainingcontainer** for the **Container id**
    
    1. Enter **/userid** for the **Partition key**
