# MVC

HTTP get request: 

> RESTfull API; set of rules that says this is the type of quests this API handles (supports CRUD method)
Create: request type that makes data (POST)
Read: requests data from server to 'read' (GET)
Update: updates pre-existing server data (PUT)
Destroy: (DELETE)

Async Solution 1 (callback): 
Callback: function passed as an argument called at a later time
        getData(drawData){
            asyncProcess()
            drawData()
        }

Async Solution 2 (promise):
A method can return a promise which has methods for success (.then) and failure (.catch)
        getData().THEN(d =>proxyState.data = d).catch(error...._)

Async Solution 3 (async/await)

methods can be flagged as 'async' inside the function keyword 'await'


AXIOSm'-api Butler'

    > Create instance of Axios with baseurl
    >let hpApi = axios.create({
        baseURL:  *website URL* http://hp-api.herokuapp.com/api,
        timeout: 3000
    })

    Get Request
    let response = await hpApi.get('characters'..........)