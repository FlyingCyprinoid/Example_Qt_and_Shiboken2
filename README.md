# Example_Qt_and_Shiboken2
Learn how to use Shiboken2 with your own custom Qt based library

Read on our blog more about it: https://blog.basyskom.com/2019/using-shiboken2-to-create-python-bindings-for-a-qt-library/

#
编译有下面问题未解决
qobjectwithenum_wrapper.cpp.obj : error LNK2019: 无法解析的外部符号 "public: static struct QMetaObject const QObjectWithEnum::staticMetaObject" (?staticMetaObject@QObjectWithEnum@@2UQMetaObject@@B)，该符号在函数 "int __cdecl qRegisterMetaType<enum QObjectWithEnum::MyEnum>(char const *,enum QObjectWithEnum::MyEnum *,enum QtPrivate::MetaTypeDefinedHelper<enum QObjectWithEnum::MyEnum,1>::DefinedType)" (??$qRegisterMetaType@W4MyEnum@QObjectWithEnum@@@@YAHPEBDPEAW4MyEnum@QObjectWithEnum@@W4DefinedType@?$MetaTypeDefinedHelper@W4MyEnum@QObjectWithEnum@@$00@QtPrivate@@@Z) 中被引用
