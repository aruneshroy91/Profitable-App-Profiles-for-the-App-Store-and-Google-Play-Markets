# Profitable-App-Profiles-for-the-App-Store-and-Google-Play-Markets
Analyze data to understand what type of apps are likely to attract more users
## Description of the Apple Store dataset 
One can find the dataset [here](https://www.kaggle.com/ramamet4/app-store-apple-data-set-10k-apps).

The columns headers descriptions are:-
* "id" : App ID
* "track_name": App Name
* "size_bytes": Size (in Bytes)
* "currency": Currency Type
* "price": Price amount
* "ratingcounttot": User Rating counts (for all version)
* "ratingcountver": User Rating counts (for current version)
* "user_rating" : Average User Rating value (for all version)
* "userratingver": Average User Rating value (for current version)
* "ver" : Latest version code
* "cont_rating": Content Rating
* "prime_genre": Primary Genre
* "sup_devices.num": Number of supporting devices
* "ipadSc_urls.num": Number of screenshots showed for display
* "lang.num": Number of supported languages
* "vpp_lic": Vpp Device Based Licensing Enabled

## Description of the Google playstore dataset
The link to the description of the dataset is [here](https://www.kaggle.com/lava18/google-play-store-apps)
* "App" : Application name
* "Category" : Category the app belongs to
* "Rating" : Overall user rating of the app (as when scraped)
* "Reviews" : Number of user reviews for the app (as when scraped)
* "Size" : Size of the app (as when scraped)
* "Installs" : Number of user downloads/installs for the app (as when scraped)
* "Type" : Paid or Free
* "Price" : Price of the app (as when scraped)
* "Content Rating" : Age group the app is targeted at - Children / Mature 21+ / Adult
* "Genres" : An app can belong to multiple genres (apart from its main category). For eg, a musical family game will belong to Music, Game, Family genres.

## Data Cleaning
We are interested in free English apps

### Remove duplicate entries
Check whether the data contains any app data for multiple times.

### Cleaned for unique data
We curated a dictonary using the number of reviews as stated above to find the app data corresponsing to the maximum number of reviews. 

### iOS data do not contain duplicate entries

### Filter non-English apps
We will focus here only on the English apps

### Find an app profile that fits both the App Store and Google Play

### Analysis of "prime_genre" in App Store data
* The most common genre is "Games". The second most common genre is "Entertaiment"
* The least common genre is "Catalog".
* Most apps are designed for entertainment purpose (games, photo and videos etc) as opposed to the practical purposes (education, shopping, utilities etc)

### App Store app recommnedation
Besed on the analysis above based on user rating per genre, the recommended app profile should be "Games".

### Analysis of "Category" and "Genres" in Play Store data
* Tools, Entertainment, Education, Business are the most common genres.
* Apps for practical and well as for entertainment is present which is in contrast with the App Store data.
* An app which can cover both entertainment and gaming genre can become a profitable app.
* The frequncy tables indicate that the app genres with most frequency can be the apps with most users. But some other parameters must be considered before a concrete conclusion. 

### Most profitable app profile
App that deals with productivity will be the most profitable app profile.
