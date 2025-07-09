# PH-Mobile-Carrier-Statistical-Analysis

#Problem Statement 

NBA has a partnership with Smart communications in the Philippines, whereby Smart is able to sell NBA League Pass Monthly SKU to their customers for a price 15% lower than retail on NBA.com or NBA App

However, the penetration of NBA LP within Smart's customer base is really small and as we enter the renewal discussion I wanted to find out the TAM of the market for Smart's potential sales

Previously I looked at Smart's FY24 financial results and estimated there are around 2M postpaid susbcribers, and estimated >21M prepaid customers, which would put NBA LP subscriber penetration at <10%

Then I realised that mobile carrier information is available when you create a customer cohort on Amplitude, which was the case. Some were missing and I had to find out the carrier information from WHOIS lookup by using IP address data from Amplitude user IDs

After that, I wanted to find out how many NBA App users, that don't have NBA LP subscription, are actually using the NBA App in Philippines. This would consistute the TAM that Smart could sell to. By running this analysis and sampling the large dataset to draw a statistical conclusion that could be applied to the entire population of NBA App users without LP but using Smart mobile carrier network, we can identify that around 40% of users are Smart mobile customers, which represents a more solid TAM than looking at their total customer base
