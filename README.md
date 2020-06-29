# leacoinsource
leacoinsource


In rpcrawtransations.cpp:

-                const CScriptID& hash = boost::get<const CScriptID&>(address);
+                const CScriptID& hash = boost::get<CScriptID>(address);
