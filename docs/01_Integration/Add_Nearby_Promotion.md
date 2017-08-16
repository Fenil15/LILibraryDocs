**Nearby Promotion** will add ability to show nearby promotions along with search and filter capabilities..

[TOC]

## For Android

### Activity

```
SampleNearbyPromotionListActivity.fnStartActivity(context, strSecretKey);
```

Where        |  
:-----:|:----:
context      | Instance of Context class    
strSecretKey | String instance, Project specific secret key shared with you    



<!--`Where context = Instance of Context class`
`      strSecretKey = Project specific secret key shared with you` -->

### Fragment

```
LitmusNearbyPromotionFragment.newInstance(context, strSecretKey, showNearbyOffers, arrOptionalNearbyOffers, nDefaultOfferImageResourceId);
```

Where        |  
:-----:|:----:
context                | Instance of Context class    
strSecretKey | String instance, Project specific secret key shared with you  
showNearbyOffers       | boolean variable, true if optional nearby variable is null    
arrOptionalNearbyOffers| ArrayList<OffersBO> instance, null if getting it from Litmus Nearby promotion Api else not null in case of custom Nearby Promotions from any other server
nDefaultOfferImageResourceId | int variable, offer image resource id to be shown in case promotion image is being downloaded / download fails




## For iOS

### ViewController

### View