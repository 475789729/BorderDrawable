android的view没有设置边框的功能。网上一般是新建xml文件，然后设置view的背景。
有了这个类，就不需要新建xml文件了，直接返回一个边框的drawable，设置成view的背景就行了。并且可以在设置边框的同时保持背景的透明性。
