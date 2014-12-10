---
title:  "Test Post"
date:   2014-12-09 00:43:00
categories: tests
---

**Title of a Section**

> They who can give up essential liberty to obtain a little temporary safety, deserve neither liberty nor safety.
> 
> _Benjamin Franklin_

**Code**

```c
- (UITableViewCell*)tableView:(UITableView *)tableView cellForRowAtIndexPath:(NSIndexPath *)indexPath
{
	UITableViewCell *cell = [tableView dequeueReusableCellForIdentifier:@"Cell"];

	if(!cell)
	{
		cell = [[UITableViewCell alloc] initWithStyle:UITableViewCellStyleDefault];
	}
	return cell;
}
```
