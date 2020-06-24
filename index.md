## Narrate web profiles (wraps the deeplink)

Web profiles for some production users:  

- http://narrateapp.com/hung
- https://narrateapp.com/robert
- https://narrateapp.com/allan  
- https://narrateapp.com/meghan
- https://narrateapp.com/billy
 
 
Web profiles for some qa users:  

- https://qa.narrateapp.com/robert
- https://qa.narrateapp.com/hqqa2  
- https://qa.narrateapp.com/hqqa3
- https://qa.narrateapp.com/hqqa
 
 
## Narrate direct deeplink profiles
 Here are the 5 variations on potential deeplinks (universal + branch link)

```
On QA: 

1. Branch ugly deep link: https://9cwbj-alternate.test-app.link?%24username=${username}
2. Branch domain deep link: https://staging.narrateapp.com?%24username=${username}
3. Direct ugly universal link: https://9cwbj-alternate.test-app.link/profile/${username}
4. Direct Domain universal link: https://staging.narrateapp.com/profile/${username}
5. Hybrid ugly deep link: https://9cwbj-alternate.test-app.link/profile/${username}?%24username=${username}
6. Hybrid domain deep link: https://staging.narrateapp.com/profile/${username}?%24username=${username}
```


1. Branch ugly deep link: https://9cwbj-alternate.test-app.link?%24username=${username}:  
   [hqqa2](https://9cwbj-alternate.test-app.link?%24username=hqqa2)  
   [hqqa3](https://9cwbj-alternate.test-app.link?%24username=hqqa3)  
   [robert](https://9cwbj-alternate.test-app.link?%24username=robert)  
   
2. Branch domain deep link: https://staging.narrateapp.com?%24username=${username}:  
   [hqqa2](https://staging.narrateapp.com?%24username=hqqa2)  
   [hqqa3](https://staging.narrateapp.com?%24username=hqqa3)  
   [robert](https://staging.narrateapp.com?%24username=robert)  
   
3. Direct ugly universal link: https://9cwbj-alternate.test-app.link/profile/${username}:  
   [hqqa2](https://9cwbj-alternate.test-app.link/hqqa2)  
   [hqqa3](https://9cwbj-alternate.test-app.link/hqqa3)  
   [robert](https://9cwbj-alternate.test-app.link/robert)  


4. Direct Domain universal link: https://staging.narrateapp.com/profile/${username}:  
   [hqqa2](https://staging.narrateapp.com/profile/hqqa2)  
   [hqqa3](https://staging.narrateapp.com/profile/hqqa3)  
   [robert](https://staging.narrateapp.com/profile/robert)  

5. Hybrid ugly deep link: https://9cwbj-alternate.test-app.link/profile/${username}?%24username=${username}:  
   [hqqa2](https://staging.narrateapp.com/profile/hqqa2?%24username=hqqa2)  
   [hqqa3](https://staging.narrateapp.com/profile/hqqa3?%24username=hqqa3)  
   [robert](https://staging.narrateapp.com/profile/robert?%24username=robert)   

6. Hybrid domain deep link: https://staging.narrateapp.com/profile/${username}?%24username=${username}:  
   [hqqa2](https://staging.narrateapp.com/profile/hqqa2?%24username=hqqa2)  
   [hqqa3](https://staging.narrateapp.com/profile/hqqa3?%24username=hqqa3)  
   [robert](https://staging.narrateapp.com/profile/robert?%24username=robert)  
   
   
``` 
On Live Production:

1. Branch ugly deep link: https://9cwbj-alternate.app.link?%24username=${username}
2. Branch domain deep link: https://beta.narrateapp.com?%24username=${username}
3. Direct ugly universal link: https://9cwbj-alternate.app.link/profile/${username}
4. Direct universal link: https://beta.narrateapp.com/profile/${username}
5. Hybrid ugly deep link: https://9cwbj-alternate.app.link/profile/${username}?%24username=${username}
6. Hybrid domain deep link: https://beta.narrateapp.com/profile/${username}?%24username=${username}
```
1. Branch ugly deep link: https://9cwbj-alternate.app.link?%24username=${username}:  
   [hung](https://9cwbj-alternate.app.link?%24username=hung)  
   [allan](https://9cwbj-alternate.app.link?%24username=allan)  
   [billy](https://9cwbj-alternate.app.link?%24username=billy)  
   
2. Branch domain deep link: https://staging.narrateapp.com?%24username=${username}:  
   [hung](https://beta.narrateapp.com?%24username=hung)  
   [allan](https://beta.narrateapp.com?%24username=allan)  
   [billy](https://beta.narrateapp.com?%24username=billy)  
   
3. Direct ugly universal link: https://9cwbj-alternate.test-app.link/profile/${username}:  
   [hung](https://9cwbj-alternate.app.link/hung)  
   [allan](https://9cwbj-alternate.app.link/allan)  
   [billy](https://9cwbj-alternate.app.link/billy)  


4. Direct Domain universal link: https://staging.narrateapp.com/profile/${username}:  
   [hung](https://beta.narrateapp.com/profile/hung)  
   [allan](https://beta.narrateapp.com/profile/allan)  
   [billy](https://beta.narrateapp.com/profile/billy)  

5. Hybrid ugly deep link: https://9cwbj-alternate.test-app.link/profile/${username}?%24username=${username}:  
   [hung](https:///9cwbj-alternate.app.link/profile/hqqa2?%24username=hung)  
   [allan](https:///9cwbj-alternate.app.link/profile/hqqa3?%24username=allan)  
   [billy](https:///9cwbj-alternate.app.link/profile/robert?%24username=billy)  

6. Hybrid domain deep link: https://staging.narrateapp.com/profile/${username}?%24username=${username}:  
   [hung](https://beta.narrateapp.com/profile/hqqa2?%24username=hung)  
   [allan](https://beta.narrateapp.com/profile/hqqa3?%24username=allan)  
   [billy](https://beta.narrateapp.com/profile/robert?%24username=billy)  
