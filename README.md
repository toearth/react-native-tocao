# react-native-tocao

1. react最近的行为有点诡异，react16的ComponentWillMount,会执行两次。如果在里面放了加载数据的函数，会加载两遍。第一遍不管读没读完数据，state都会初始化，第二遍是正常的行为。
