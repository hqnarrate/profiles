## Narrate web profiles 

Web profiles for some production users:  

- http://narrateapp.com/hung
- [Robert](https://narrateapp.com/robert)  
- [Allan](https://narrateapp.com/allan)  
- Meghan [https://narrateapp.com/meghan](https://narrateapp.com/meghan)  
- [Billy]https://narrateapp.com/billy  
 
 
Web profiles for some qa users:  

- [Robert](https://qa.narrateapp.com/robert) https://qa.narrateapp.com/robert  
- [hqqa2](https://qa.narrateapp.com/hqqa2) https://qa.narrateapp.com/hqqa2  
- [hqqa3](https://qa.narrateapp.com/hqqa3) https://qa.narrateapp.com/hqqa3  
- [hqqa](https://qa.narrateapp.com/hqqa) https://qa.narrateapp.com/hqqa  
 
 
## Narrate direct deeplink profiles
 Here are the 5 variations on potential deeplinks (universal + branch link)

```
On QA: 

1. Branch ugly deep link: https://9cwbj-alternate.test-app.link?%24username=${username}
2. Branch domain deep link: https://staging.narrteapp.com?%24username=${username}
3. Direct universal link: https://staging.narrateapp.com/profile/${username}
4. Hybrid ugly deep link: https://9cwbj-alternate.test-app.link/profile/${username}?%24username=${username}
5. Hybrid domain deep link: https://staging.narrateapp.com/profile/${username}?%24username=${username}

On Live Production:
1. Branch ugly deep link: https://9cwbj-alternate.app.link?%24username=${username}
2. Branch domain deep link: https://beta.narrteapp.com?%24username=${username}
3. Direct universal link: https://beta.narrateapp.com/profile/${username}
4. Hybrid ugly deep link: https://9cwbj-alternate.app.link/profile/${username}?%24username=${username}
5. Hybrid domain deep link: https://beta.narrateapp.com/profile/${username}?%24username=${username}
```


1. Branch ugly deep link: https://9cwbj-alternate.test-app.link?%24username=${username}:  
   [hqqa2](https://9cwbj-alternate.test-app.link?%24username=hqqa2)  
   [hqqa3](https://9cwbj-alternate.test-app.link?%24username=hqqa3)  
   [robert](https://9cwbj-alternate.test-app.link?%24username=robert)  
   
2. Branch domain deep link: https://staging.narrteapp.com?%24username=${username}:  
   [hqqa2](https://staging.narrteapp.com?%24username=hqqa2)  
   [hqqa3](https://staging.narrteapp.com?%24username=hqqa3)  
   [robert]((https://staging.narrteapp.com?%24username=robert)  
   
3. Direct universal link: https://staging.narrateapp.com/profile/${username}:  
   [hqqa2](https://staging.narrteapp.com/profile/hqqa2)  
   [hqqa3](https://staging.narrteapp.com/profile/hqqa3)  
   [robert]((https://staging.narrteapp.com/profile/robert)  


4. Hybrid ugly deep link: https://9cwbj-alternate.test-app.link/profile/${username}?%24username=${username}:  
   [hqqa2](https://staging.narrteapp.com/profile/hqqa2?%24username=hqqa2)  
   [hqqa3](https://staging.narrteapp.com/profile/hqqa3?%24username=hqqa3)  
   [robert](https://staging.narrteapp.com/profile/robert?%24username=robert)   

5. Hybrid domain deep link: https://staging.narrateapp.com/profile/${username}?%24username=${username}:  
   [hqqa2](https://staging.narrteapp.com/profile/hqqa2?%24username=hqqa2)  
   [hqqa3](https://staging.narrteapp.com/profile/hqqa3?%24username=hqqa3)  
   [robert]((https://staging.narrteapp.com/profile/robert?%24username=robert)  

