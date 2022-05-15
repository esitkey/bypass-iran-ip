فایل iran.dat را دانلود کنید

فایل را از طریق Route -> Three dots -> Manage Route Assets به کلاینت اضافه کنید.
sagernet

از بخش Route -> Create Route قوانین زیر را اضافه کنید:
Block Ads:

domain: geosite:category-ads-all

outbound: Block

Block Iran Ads:

domain: ext:iran.dat:ads

outbound: Block

Bypass Iran .ir Domains:

domain: regexp:.+\.ir$

outbound: Bypass

Bypass Iran non .ir Domains:

domain: ext:iran.dat:other

outbound: Bypass

Bypass Iran geoip:

ip: geoip:ir

outbound: Bypass

اتصال خود را قطع و وصل کنید.
پایان
