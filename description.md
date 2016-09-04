
```
class Library 
{
	...
	class ItemContainer
	{
		...
		class RelatedWork
		{
			...
		}
	}
}

```

```
Library keeps [ ItemContainer1, ItemContainer2, ItemContainer3.....]

ItemContainer_1:
	shared_ptr itemPtr_1;
	[ RelatedWork_1_1, RelatedWork_2_2, RelatedWork_3_3......]

ItemContainer_2:
	shared_ptr itemPtr_2;
	[ RelatedWork_2_1, RelatedWork_2_2, RelatedWork_3_3......]	

ItemContainer_1 relates to ItemContainer_2:
	RelatedWork_1_1: 
		relatedLink = ItemContainer_2.itemPtr_2;
```


