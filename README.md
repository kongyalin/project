# project
//a function about uuid (16 all number)
String str = "";
str = String.format("%016d", CommUtil.null2String(UUID.randomUUID()).hashCode());//将原来带字母的32位UUID嘛变成16位纯数字
