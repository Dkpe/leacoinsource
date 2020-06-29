# leacoinsource
leacoinsource


In rpcrawtransations.cpp:
#
REM                const CScriptID& hash = boost::get<const CScriptID&>(address);
ADD                const CScriptID& hash = boost::get<CScriptID>(address);
#
