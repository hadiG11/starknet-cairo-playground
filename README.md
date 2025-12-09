# starknet-cairo-playground
Learning Cairo &amp; Starknet contracts | tea farmer #420 to #1 
**Day 1 - 18 Nov 2025** Set up Starknet dev environment and wrote first Hello World in Cairo | Streak 1/100 ☕ #tea #Starknet

**Day 2 - 19 Nov 2025** Explored Cairo syntax basics and tested simple variables/storage | Streak 2/100 🫖 #tea #Starknet

**Day 3 - 20 Nov 2025** Cairo storage + simple contract tested | Streak 3/100 ☕ #tea #Starknet

**Day 4 - 21 Nov 2025** Cairo functions explored + contract deployment tested | Streak 4/100 🫖 #tea #Starknet

**Day 5 - 22 Nov 2025** Built and deployed a basic Cairo event-emitting contract on Starknet testnet, optimizing for storage efficiency | Streak 5/100 ☕ #TeaProtocol #Starknet #CairoLang #OSSImpact #AirdropRewardsDay 6 - 23 Nov 2025 Explored mappings and key-value storage in Cairo contracts, integrated into a test contract | Streak 6/100  #TeaProtocol #Starknet #CairoLang #OSSImpact #AirdropRewardsDay 7 - 24 Nov 2025 Learned about structs and enums in Cairo, built and deployed a sample contract using them on testnet | Streak 7/100  #TeaProtocol #Starknet #CairoLang #OSSImpact #AirdropRewards

Day 8 - 25 Nov 2025: Explored arrays, loops in Cairo; deployed iterative contract on testnet | Streak 8/100 #TeaProtocol #Starknet #CairoLang #OSSImpact #AirdropRewards
Day 9 - 26 Nov 2025: Explored conditionals, if-else, and match in Cairo; deployed decision-logic contract on testnet | Streak 9/100  #TeaProtocol #Starknet #CairoLang #OSImpact #AirdropRewards

Day 10 - 27 Nov 2025: Explored functions and recursion in Cairo; deployed a recursive logic contract on testnet | Streak 10/100  #TeaProtocol #Starknet #CairoLang #OSSImpact #AirdropRewards
28 Nov 2025: Daily Tea farming check-in with testnet quest completion

November 29, 2025: Updated tea.yaml with new ZK proof config for value layer integration.

Day 12 - 29 Nov 2025: Explored arrays and loops in Cairo; deployed an iterative contract on testnet for Tea integration testing. Catching up on missed day. Streak 12/100 #TeaProtocol #Starknet #CairoLang #OSSImpact #AirdropRewards

Day 13 - 30 Nov 2025: Learned conditionals, if-else, and match in Cairo; built and deployed a decision-logic contract on testnet, optimizing for storage efficiency. Streak 13/100 #TeaProtocol #Starknet #CairoLang #OSSImpact #AirdropRewards
 01 Dec,day 14 2025: Daily Tea farming check-in with testnet quest update; optimized tea.yaml for function-based ZK integrations.Day 15 (Dec 02, 2025): Explored enums and structs in Cairo; deployed a structured data contract on testnet, enhancing Tea Protocol integration for OSS rewards. Streak 14/100 #TeaProtocol #Starknet #CairoLang #OSSImpact #AirdropRewards
Tested Cairo Playground functions and checked output correctness. Logged minor differences in computation time.Dec 3
Tested Cairo Playground functions and checked output correctness. Logged minor differences in computation time.Dec 4
Reviewed Tea docs update and validated a basic contract execution on the testnet environment.Dec 5
Ran a small Cairo script and compared gas cost before and after optimizationDec 6
Debugged a failing function; issue traced to wrong argument indexing. Documented the fix.Dec 7
Implemented a small Cairo test routine to verify storage reads under concurrent calls; logged delta in execution cost and updated the validation notes for reproducibility.Starknet Cairo-Dec 08,2025:Simple factorial func:func factorial(n: felt)->(res: felt) { if (n == 0){return(res=1); }let(res)=factorial(n-1); return(res=n*res);}
Test:factorial(5)=120,daily practice for streak
Tea Protocol Streak 15/100 - Dec 09, 2025: Explored Cairo array sum: func sum_array(arr: felt*, len: felt) -> (sum: felt) { if (len == 0) { return (sum=0); } let (rest_sum) = sum_array(arr+1, len-1); return (sum = [arr] + rest_sum); }
Test: sum_array([1,2,3],3)=6, daily streak practice. 
#TeaProtocol #Starknet #CairoLang #OSSImpact #AirdropRewards

Tea Protocol Streak 16/100 - Dec 10, 2025: Tested Cairo's struct handling: struct Point { x: felt, y: felt, } func add_points(p1: Point, p2: Point) -> (res: Point) { return (res = Point(x = p1.x + p2.x, y = p1.y + p2.y)); }
Test: add_points(Point(1,2), Point(3,4)) = Point(4,6), streak practice. 
#TeaProtocol #Starknet #CairoLang #OSSImpact #AirdropRewards
