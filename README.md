# Suno API (start integrating in just 1 min!)
(Go to <a href="https://github.com/Goapiai/Suno-API?tab=readme-ov-file#usage-steps">Usage Steps</a> and follow the steps 1~3!)
- no private deploymenet needed!
- no downloading code!
- no need for your own Suno Account(s)!

<br>

<p>Enhance your website/app's music creation capability with the unofficial Suno API from GoAPI, designed to boost your users' text-to-music generation capabilities! Find out more at <a href="https://www.goapi.ai/suno-api"> Suno API</a> !</p>
<p align="left">
<img src="https://github.com/Goapiai/Suno-API/assets/149752566/d8809cd5-a8e4-4820-94c4-0c425cda473a" alt="screenshot of the Suno API page from GoAPI" width="95%" title="hover text">
</p>
<br>

## Features

1. Create API
2. Continue API
3. Lyrics Generation API
4. High Concurrency
5. V3 model supported
6. Asynchronous calls
7. Pay-per-use (PPU) option supported!
8. BYOA (Bring-your-own-account) option coming soon!
<br>

## Usage Options 

### PPU Option (Available!)
<p> Pay-per-use (PPU): Just top up credits at <a href="https://dashboard.goapi.ai/"> GoAPI's dashboard</a> and use the API right away! The benefit of the PPU option is that you don't need to have your own Suno accounts to use the Suno API, as you will be using our account pools instead. Please refer to this pricing table for the per-usage pricing for the API under PPU option. 
  
- Don't need your own Suno account(s) pool!
- Don't need to manage/operate Suno accounts 
- Get started with integrating the API a.s.a.p. !
- Supporting High concurrency!

**Pricing**
- $0.02/create api call (half the price as official Suno Pricing) 
- $0.04/continue api call
- FREE for Lyrics Generation! (See <a href="https://www.goapi.ai/docs/pricing-plan#suno-api-pricing"> PPU pricing table</a> for Suno API's pricing for the PPU option!)

  
</p>
<br>

### BYOA Option (coming soon!) 
<p> Bring-Your-Own-Accounts (BYOA): You will be using your own Suno account(s)' resource in this option, you will be required to buy GoAPI Suno API seat(s), bind your Suno Account(s) to the seat(s), and you are ready to go! 
  
- Already have your own Suno account(s)?
- Don't want to wait in queue for other's tasks to complete before yours commences? 
- Offers overall faster generation time!

**Pricing**
- $5/month for **two (2)** BYOA seats!

  
</p>
<br>




## Usage Steps 

### PPU 

1. Register for an account at <a href="https://dashboard.goapi.ai/"> GoAPI's dashboard </a> using your GitHub account.
2. Obtain your API KEY from <a href="https://dashboard.goapi.ai/key">Keys Page</a> .
3. Start Coding right away!
<br>

#### Sample API Calls (using cURL)

**Create API CAll**
```cURL
curl --location 'https://api.goapi.ai/api/suno/v1/music' \
--header 'X-API-Key: your_api_key_here' \
--header 'Content-Type: application/json' \
--data '{
  "custom_mode": false,
  "input": 
        {
            "gpt_description_prompt":"space travel",
            "make_instrumental": false
        }
}'
```

**Returning**
```cURL
{
    "code": 200,
    "data": {
        "task_id": "record_this_taskID"
    },
    "message": "success"
}
```

**Get API Call**
```cURL
curl --location 'https://api.goapi.ai/api/suno/v1/music/{input_recorded_taskID}' \
--header 'X-API-Key: your_api_key_here'
```

**Returning**

Check out Suno API's <a href="https://www.goapi.ai/docs/suno-api"> technical documentation</a> for more information! 

<br>




## Contact 
1. Discord: https://discord.com/invite/5KZvm7UU5Q
2. Telegram: https://t.me/+6PqcdxoheXA4YmRl
3. WeChat: https://shorturl.at/bmsxG


