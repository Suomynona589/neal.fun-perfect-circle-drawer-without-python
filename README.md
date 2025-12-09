# How to make a Perfect Circle in Neal Fun's game without python!

# Step 1:
Go to ANY random website. You COULD just go to example.com, since it's an example domain with like basically nothing.

# Step 2:
Click the star in the URL bar to favorite/bookmark it.

# Step 3:
Optionally, you can rename it, possibly to something like "Perfect Circle Drawer".

# Step 4:
If you can already see all the bookmarks on bookmark bar, good. If not, use Ctrl+Shift+B to reveal them.

# Step 5:
Right-click the bookmark and click Edit.

# Step 6: Highlight the URL and delete it, then paste this into URL instead:

javascript:(function()%7Blet s%3Ddocument.querySelector("main svg").getBoundingClientRect()%2Ccx%3Ds.width%2F2%2Bs.x%2Ccy%3Ds.height%2F2%2Bs.y%2Cr%3Ds.width%2F3%2Cd%3Ddocument.querySelector("main div")%2Ca%3D0%3Bfor(let e%3D0%3Be<50%3Be%2B%2B)%7Ba%2B%3DMath.acos(1-Math.pow(60%2Fr%2C2)%2F2)%3Blet t%3DMath.round(cx%2Br*Math.cos(a))%2Cn%3DMath.round(cy%2Br*Math.sin(a))%3B0%3D%3De%26%26d.dispatchEvent(new MouseEvent("mousedown"%2C%7BclientX%3At%2CclientY%3An%7D))%2Cd.dispatchEvent(new MouseEvent("mousemove"%2C%7BclientX%3At%2CclientY%3An%7D))%7Dd.dispatchEvent(new MouseEvent("mouseup"))%7D)()

# Step 7:
Save and go to https://neal.fun/perfect-circle. Click the Go thing in the middle to start.

# Step 8: Click the 'Perfect Circle Drawer' bookmark, and there you go!
