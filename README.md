# Vigenère cryptanalysis


The code above implements Vigenère cipher and performs a cryptanalysis using character sequence analysis.

# Testing the code
**NOTE: All the input must be in Caps**

### 1. Encryption 
**Step 1:** Generate a plaintext of a minimum of 200 characters and a key that is less than a plaintext. If the key is greater than the plaintext, the code will trim the key to the plaintext's length, whereas if the plaintext is larger, the key is repeated till it covers the entire message.

**Step 2:** Once the plaintext and key are generated, compile the file vigenereEncryption.cpp and provide it with your input (plaintext and the key). The program output will be a ciphertext.

Compile the code in --o2 for best results.

### 2. Cryptanalysis

**Step 1:** Copy the ciphertext from the previous file. Compile the file vigenereCryptanalysis.cpp and input the result from the last step. The code will give you its best guesses of the key.

Compile the code in --o2 for best results. 

# Example: Encryption

**Please enter your plaintext:** THEFIRSTWELLDOCUMENTEDDESCRIPTIONOFAPOLYALPHABETICCIPHERWASBYLEONBATTISTAALBERTIANDUSEDAMETALCIPHERDISKTOSWITCHBETWEENCIPHERALPHABETSALBERTISSYSTEMONLYSWITCHEDALPHABETSAFTERSEVERALWORDSANDSWITCHESWEREINDICATEDBYWRITINGTHELETTEROFTHECORRESPONDINGALPHABETINTHECIPHERTEXTLATERJOHANNESTRITHEMIUSINHISWORKPOLYGRAPHIAEWHICHWASCOMPLETEDINMANUSCRIPTFORMBUTFIRSTPUBLISHEDLATERINVENTEDTHETABULARECTAACRITICALCOMPONENTOFTHEVIGENERECIPHERTHETRITHEMIUSCIPHERHOWEVERPROVIDEDAPROGRESSIVERATHERRIGIDANDPREDICTABLESYSTEMFORSWITCHINGBETWEENCIPHERALPHABETSTHECIPHERNOWKNOWNASTHEVIGENERECIPHERHOWEVERISTHATORIGINALLYDESCRIBEDBYGIOVANBATTISTABELLASOINHISBOOKLACIFRADELSIGGIOVANBATTISTABELLASOHEBUILTUPONTHETABULARECTAOFTRITHEMIUSBUTADDEDAREPEATINGCOUNTERSIGNAKEYTOSWITCHCIPHERALPHABETSEVERYLETTERWHEREASALBERTIANDTRITHEMIUSUSEDAFIXEDPATTERNOFSUBSTITUTIONSBELLASOSSCHEMEMEANTTHEPATTERNOFSUBSTITUTIONSCOULDBEEASILYCHANGEDSIMPLYBYSELECTINGANEWKEYKEYSWERETYPICALLYSINGLEWORDSORSHORTPHRASESKNOWNTOBOTHPARTIESINADVANCEORTRANSMITTEDOUTOFBANDALONGWITHTHEMESSAGEBELLASOSMETHODTHUSREQUIREDSTRONGSECURITYFORONLYTHEKEYASITISRELATIVELYEASYTOSECUREASHORTKEYPHRASESUCHASBYAPREVIOUSPRIVATECONVERSATIONBELLASOSSYSTEMWASCONSIDERABLYMORESECUREINTHENINETEENTHCENTURYTHEINVENTIONOFBELLASOSCIPHERWASMISATTRIBUTEDTOVIGENEREDAVIDKAHNINHISBOOKTHECODEBREAKERSLAMENTEDTHISMISATTRIBUTIONSAYINGTHATHISTORYHADIGNOREDTHISIMPORTANTCONTRIBUTIONANDINSTEADNAMEDAREGRESSIVEANDELEMENTARYCIPHERFORHIMVIGENERETHOUGHHEHADNOTHINGTODOWITHITTHEVIGENERECIPHERGAINEDAREPUTATIONFORBEINGEXCEPTIONALLYSTRONGNOTEDAUTHORANDMATHEMATICIANCHARLESLUTWIDGEDODGSONLEWISCARROLLCALLEDTHEVIGENERECIPHERUNBREAKABLEINHISPIECETHEALPHABETCIPHERINACHILDRENSMAGAZINEINSCIENTIFICAMERICANDESCRIBEDTHEVIGENERECIPHERASIMPOSSIBLEOFTRANSLATIONTHATREPUTATIONWASNOTDESERVEDCHARLESBABBAGEISKNOWNTOHAVEBROKENAVARIANTOFTHECIPHERASEARLYBUTDIDNOTPUBLISHHISWORKKASISKIENTIRELYBROKETHECIPHERANDPUBLISHEDTHETECHNIQUEINTHENINETEENTHCENTURYBUTEVENINTHESIXTEENTHCENTURYSOMESKILLEDCRYPTANALYSTSCOULDOCCASIONALLYBREAKTHECIPHERTHEVIGENERECIPHERISSIMPLEENOUGHTOBEAFIELDCIPHERIFITISUSEDINCONJUNCTIONWITHCIPHERDISKSTHECONFEDERATESTATESOFAMERICAFOREXAMPLEUSEDABRASSCIPHERDISKTOIMPLEMENTTHEVIGENERECIPHERDURINGTHEAMERICANCIVILWARTHECONFEDERACYSMESSAGESWEREFARFROMSECRETANDTHEUNIONREGULARLYCRACKEDITSMESSAGESTHROUGHOUTTHEWARTHECONFEDERATELEADERSHIPPRIMARILYRELIEDUPONTHREEKEYPHRASESMANCHESTERBLUFFCOMPLETEVICTORYANDASTHEWARCAMETOACLOSECOMERETRIBUTIONTHEFIRSTWELLDOCUMENTEDDESCRIPTIONOFAPOLYALPHABETICCIPHERWASBYLEONBATTISTAALBERTIANDUSEDAMETALCIPHERDISKTOSWITCHBETWEENCIPHERALPHABETSALBERTISSYSTEMONLYSWITCHEDALPHABETSAFTERSEVERALWORDSANDSWITCHESWEREINDICATEDBYWRITINGTHELETTEROFTHECORRESPONDINGALPHABETINTHECIPHERTEXTLATERJOHANNESTRITHEMIUSINHISWORKPOLYGRAPHIAEWHICHWASCOMPLETEDINMANUSCRIPTFORMBUTFIRSTPUBLISHEDLATERINVENTEDTHETABULARECTAACRITICALCOMPONENTOFTHEVIGENERECIPHERTHETRITHEMIUSCIPHERHOWEVERPROVIDEDAPROGRESSIVERATHERRIGIDANDPREDICTABLESYSTEMFORSWITCHINGBETWEENCIPHERALPHABETSTHECIPHERNOWKNOWNASTHEVIGENERECIPHERHOWEVERISTHATORIGINALLYDESCRIBEDBYGIOVANBATTISTABELLASOINHISBOOKLACIFRADELSIGGIOVANBATTISTABELLASOHEBUILTUPONTHETABULARECTAOFTRITHEMIUSBUTADDEDAREPEATINGCOUNTERSIGNAKEYTOSWITCHCIPHERALPHABETSEVERYLETTERWHEREASALBERTIANDTRITHEMIUSUSEDAFIXEDPA

**Key:** SWAPNILPALIWALARUNRAMMOHANARETHETWOCONTRIBUTORSFORTHISPROJECT

**Ciphertext:** LDEUVZDIWPTHDZCLGRETQPRLSPRZTMPSGKTCDBEPIMJAOSWYWTVPXZTIKJWDRDAOCOIEIIDBWAWBVLGZAZPIZEQADIMHPVEDJSEWZALNHGNAYQYULBOTVBLMRAWNAACPLQEEAWLMEINVJSKEHLMBNCCLDMMYVGRNEGPBVXHJSKHVKZMNTIOUAQKVOACQAHXTNPASHEIYVEDUOOAEQBPAKPXBJUVVREVBUYKCWLMSTHYZWHGCWHKGYWLEUIMTTTVPHPCZJUVRFQLALNTVVCVLTJBGGGKZBIYFWLKNBYBZEGGBDXPAZJWPWVIPLHTKDWLSTIZGLQFSKIAMRRNZGKEDVTBKDJVNYWIKYDLUSQKWVRUEVXJENKRVETDEPATLBLFNIEOFOHCEIKMVHPVKARCAXEBPZMVVNNUVGLZWRZDQITMZATGVBSTMTCOCTPYYEYOIQJLRCRFZBKIWWDTCTKVATCOSISYVVKYQYXUOWHRKWZIRGIMAEDGOTPMWIEJWUFQOIAGSIMDIXJQKDUXIIMJAOSWYGKALKAEYSARQPCJOLAIDIHPDEGPNVLRTIBTSYHBWVZXYMLPVCHBKZOJHTZCQISJVYQTTUPHKKHNWNQNBEXSEIXEWLRMBZNTUGIOBKCEVPJKWRGZFBXOJIOOETFHKBZBSQVZUEUHZABJVTEJPZVPHPTRVHCADQQAABFKVBALXIWWGONKIEXXRRJJDVTAQFVTCDRVXJOIVAIVTYEWOWTTTBPZPTQFHLCHRFXAWXRSTMYXKBFLPVVJJOJTSJWGKWJRFMJETWRUTJSFAADLFZRRUPMFHLRAOWWNIWMEHWHVHEACYEZRKTGJVOMETDSJRVMZAPPGBPGNZNOUMSKCGLTUABZCBUCHULITOWNMPARVHYWGZEUZPUFAWAVQCMPZSJELXMJZEJASECEKSCZCMXZFSVNXPXDSKZGQFFAFZUJAFRKJGBGVEFIFPXXJISNTXRATCAODWNNEFLGIAZEAPTGEUSNASYXOPRNEFVHQBHYLMSDXZASVVPNPNTKKSBRBSDDEPQSCEHOVIEPEHYOAGJIVBVBPMHCEHETZNASBWDOJBAQKGVZJXKOWHYTNAJIODMYUCERMUFRFWSFPURRWXZYVDOUPLTGZFPBCLKUFZOHBWRFBEITLSPIDAJPALLAKSDYJNRDWMEQVNFIUIKHFEUAQFRLVKVLXWELMSEBUMLTVBCLEXFPUGLBSTIYDANEIFHBWBQXZHSBSTMIOIKSOUAVLRBULBPLLJRKHCQYTESAIFTNEDZNPYXNSQOBZOBNUVCAPSIRRABIKZPTISPHRWKPJMFWJSYHIBICLXFBBEABFCTWNBSXSEWNYSAUCTEODQRAHVSZQIVVMWBVQBGKZJVNHZGSOEWPVKIVOMRCFWZAGROCTSDQRELNUYYVMQZHHRLCZTALVYKFJWZOZOFHXFVLMCLZOPWWRRWSVAAJGIBLZLIEPETEHVPVXEZQFLCVPYIKNEBJSFOEXGCUUMWFFKCIULQFVVLLIRMAKNPYTJHTCWJGYOKYQRUFTCYAADDEMOIFWHKQVTEKIUKZVKQIKPPLYTUCMKUHFHELVANPRCWHLNACFRUTTQJPGRNVVXJMIDSTIAUIMBETPCWNBYBZXATTSCLGTDLHPOMERIAPARTNRWUZLPDSUSZAXESPRXEBUQVXEBJZBQREJFZVHVVTJQAMDXVPHTIQRTNPZACTPYYERSUYDVSFISPXVJMNOPGYTKQPHMVRLWSGNAILXFBFEUGGPDTFMCKEOKDACLVMORBNMULIFKESPUXHDOXSOKFSFHTJRJNOEMVNLWVQRTJXJWSTNZWNBFBZIONFNCLBXUGOHVSNSKROTOWUYVXEBJLXZPTWCBXAPWRZDQITTFZPJOTTHHPLPHPTVWUEICGSPNGHVRBUIMASPHUVVVUOKMSMYSMXUQFIYSBMZMWANIUKPCTFZUSZMVMXZLXQRJRLPKEGHPROHUQBNCLPWVOJATBRESGTGVOTXJXUEPWRZEWEGQCEYEIYPZPTQFPSFIDTELIGKIIVGHSMBZBSCVHWGALZAUZHRWWLWZICPWYYUYKPIZNNCGYCUBVLRQIJOLALXYCPTRWVZBNXGKSYSJHMIETIWLEHHJAXPZXWTUDMZAMRRMFTIBTSYDVSBXHPQIHSOSAMKPFPBUVFJFVVPXZTIRDVKGYPHTNUPGINIJCTVZFJRRFTSJOAFVHXYEVUGOSFLROFMPSIWKOIYYWEHVQAIVTFZTWRCYXOYZAGFLRLYPCDMQREQIKWFLWLWUGGGAIWVAACLLYVVPHZLWVQXRHXVARPGMWTAOMNSSIGJEZMMDWSYEECMXKYIKBVVEXVSFSIVISXSJFHVUWVGCITUDQFUPWXELPBAVTCKIEPAZPOZTUENEKJEFAHQOPEFAFWHAVJJHIBICLXFBCLGYANSIJMWADZKQMPNKYQUEEOFPPGIFRHMEIKZAOYIYICYMWTUNDYXYESHSMUIQGTWTIVAEPAWJAREIRHQLSQPOTEGACGBWLXNRKGXMFAXCMQYTJHNXLVUXGVNVCEHDAQRBDPLMMNTTSJSFKEYABSYFWZXVOIWWZRVNUVBTUYHVJXSMXYIDLFFMWCGVOWXGKSTSHMNETNUCPRTQPPFWEIKMGNXAAZGHGXIWGNASTGWFVLWWFSZBPENIZWBTGQYIHPKEPSEINROTXMHLRWOYEGUILPFKHUXDQVMBBYAXKFKRXGAPUAERAAWELUQNWWLAYOXPCYGVDUZAHNHSTVBWXYKFOPHMWQSMMDLTQWJALLDPKSAMPOWJTTQBSTTLJQLLRVWGRAODWAIPACGHTTHJSPHBYKPFPBUVFJFVVPXZTIHQIVKAPHTZQFHCTXDECHFQRMEDBFVVVDVHTWVHCFGGFBMMSUMVVJWWXBKIFSGFNHKVLWBARAJHTPUBOCSNCGTHUZUIEGWVIGJMIDSTOYIYICYMGKZJQZIOMJCFKTRQPFWSIUMGXGPVARPCZJUVRTAKLVRRZWMOEMKFKUVGRTMSWSJUWWSXKJQVZCEEPUSPTXFBLQEWTWSZIEBVJBAAYSAPIWVTKIEOWIUVHMIOVTHKAXHRULTDPJCQIDNAHTJCWYIHPBWBFLRLRTTMATARVTYIFPYLXIVOQWVLBLXDVSYWEZJWMCKSAWKZFWKTLBZHWTBYHNIGBRIAXBVHBRTJIOLVRHSVHRKNPFLXOJSQPVKAQSCUHAMVAWIIJFCDTDLNEXPDGU


# Example: Cryptanalysis

**Ciphertext:** LDEUVZDIWPTHDZCLGRETQPRLSPRZTMPSGKTCDBEPIMJAOSWYWTVPXZTIKJWDRDAOCOIEIIDBWAWBVLGZAZPIZEQADIMHPVEDJSEWZALNHGNAYQYULBOTVBLMRAWNAACPLQEEAWLMEINVJSKEHLMBNCCLDMMYVGRNEGPBVXHJSKHVKZMNTIOUAQKVOACQAHXTNPASHEIYVEDUOOAEQBPAKPXBJUVVREVBUYKCWLMSTHYZWHGCWHKGYWLEUIMTTTVPHPCZJUVRFQLALNTVVCVLTJBGGGKZBIYFWLKNBYBZEGGBDXPAZJWPWVIPLHTKDWLSTIZGLQFSKIAMRRNZGKEDVTBKDJVNYWIKYDLUSQKWVRUEVXJENKRVETDEPATLBLFNIEOFOHCEIKMVHPVKARCAXEBPZMVVNNUVGLZWRZDQITMZATGVBSTMTCOCTPYYEYOIQJLRCRFZBKIWWDTCTKVATCOSISYVVKYQYXUOWHRKWZIRGIMAEDGOTPMWIEJWUFQOIAGSIMDIXJQKDUXIIMJAOSWYGKALKAEYSARQPCJOLAIDIHPDEGPNVLRTIBTSYHBWVZXYMLPVCHBKZOJHTZCQISJVYQTTUPHKKHNWNQNBEXSEIXEWLRMBZNTUGIOBKCEVPJKWRGZFBXOJIOOETFHKBZBSQVZUEUHZABJVTEJPZVPHPTRVHCADQQAABFKVBALXIWWGONKIEXXRRJJDVTAQFVTCDRVXJOIVAIVTYEWOWTTTBPZPTQFHLCHRFXAWXRSTMYXKBFLPVVJJOJTSJWGKWJRFMJETWRUTJSFAADLFZRRUPMFHLRAOWWNIWMEHWHVHEACYEZRKTGJVOMETDSJRVMZAPPGBPGNZNOUMSKCGLTUABZCBUCHULITOWNMPARVHYWGZEUZPUFAWAVQCMPZSJELXMJZEJASECEKSCZCMXZFSVNXPXDSKZGQFFAFZUJAFRKJGBGVEFIFPXXJISNTXRATCAODWNNEFLGIAZEAPTGEUSNASYXOPRNEFVHQBHYLMSDXZASVVPNPNTKKSBRBSDDEPQSCEHOVIEPEHYOAGJIVBVBPMHCEHETZNASBWDOJBAQKGVZJXKOWHYTNAJIODMYUCERMUFRFWSFPURRWXZYVDOUPLTGZFPBCLKUFZOHBWRFBEITLSPIDAJPALLAKSDYJNRDWMEQVNFIUIKHFEUAQFRLVKVLXWELMSEBUMLTVBCLEXFPUGLBSTIYDANEIFHBWBQXZHSBSTMIOIKSOUAVLRBULBPLLJRKHCQYTESAIFTNEDZNPYXNSQOBZOBNUVCAPSIRRABIKZPTISPHRWKPJMFWJSYHIBICLXFBBEABFCTWNBSXSEWNYSAUCTEODQRAHVSZQIVVMWBVQBGKZJVNHZGSOEWPVKIVOMRCFWZAGROCTSDQRELNUYYVMQZHHRLCZTALVYKFJWZOZOFHXFVLMCLZOPWWRRWSVAAJGIBLZLIEPETEHVPVXEZQFLCVPYIKNEBJSFOEXGCUUMWFFKCIULQFVVLLIRMAKNPYTJHTCWJGYOKYQRUFTCYAADDEMOIFWHKQVTEKIUKZVKQIKPPLYTUCMKUHFHELVANPRCWHLNACFRUTTQJPGRNVVXJMIDSTIAUIMBETPCWNBYBZXATTSCLGTDLHPOMERIAPARTNRWUZLPDSUSZAXESPRXEBUQVXEBJZBQREJFZVHVVTJQAMDXVPHTIQRTNPZACTPYYERSUYDVSFISPXVJMNOPGYTKQPHMVRLWSGNAILXFBFEUGGPDTFMCKEOKDACLVMORBNMULIFKESPUXHDOXSOKFSFHTJRJNOEMVNLWVQRTJXJWSTNZWNBFBZIONFNCLBXUGOHVSNSKROTOWUYVXEBJLXZPTWCBXAPWRZDQITTFZPJOTTHHPLPHPTVWUEICGSPNGHVRBUIMASPHUVVVUOKMSMYSMXUQFIYSBMZMWANIUKPCTFZUSZMVMXZLXQRJRLPKEGHPROHUQBNCLPWVOJATBRESGTGVOTXJXUEPWRZEWEGQCEYEIYPZPTQFPSFIDTELIGKIIVGHSMBZBSCVHWGALZAUZHRWWLWZICPWYYUYKPIZNNCGYCUBVLRQIJOLALXYCPTRWVZBNXGKSYSJHMIETIWLEHHJAXPZXWTUDMZAMRRMFTIBTSYDVSBXHPQIHSOSAMKPFPBUVFJFVVPXZTIRDVKGYPHTNUPGINIJCTVZFJRRFTSJOAFVHXYEVUGOSFLROFMPSIWKOIYYWEHVQAIVTFZTWRCYXOYZAGFLRLYPCDMQREQIKWFLWLWUGGGAIWVAACLLYVVPHZLWVQXRHXVARPGMWTAOMNSSIGJEZMMDWSYEECMXKYIKBVVEXVSFSIVISXSJFHVUWVGCITUDQFUPWXELPBAVTCKIEPAZPOZTUENEKJEFAHQOPEFAFWHAVJJHIBICLXFBCLGYANSIJMWADZKQMPNKYQUEEOFPPGIFRHMEIKZAOYIYICYMWTUNDYXYESHSMUIQGTWTIVAEPAWJAREIRHQLSQPOTEGACGBWLXNRKGXMFAXCMQYTJHNXLVUXGVNVCEHDAQRBDPLMMNTTSJSFKEYABSYFWZXVOIWWZRVNUVBTUYHVJXSMXYIDLFFMWCGVOWXGKSTSHMNETNUCPRTQPPFWEIKMGNXAAZGHGXIWGNASTGWFVLWWFSZBPENIZWBTGQYIHPKEPSEINROTXMHLRWOYEGUILPFKHUXDQVMBBYAXKFKRXGAPUAERAAWELUQNWWLAYOXPCYGVDUZAHNHSTVBWXYKFOPHMWQSMMDLTQWJALLDPKSAMPOWJTTQBSTTLJQLLRVWGRAODWAIPACGHTTHJSPHBYKPFPBUVFJFVVPXZTIHQIVKAPHTZQFHCTXDECHFQRMEDBFVVVDVHTWVHCFGGFBMMSUMVVJWWXBKIFSGFNHKVLWBARAJHTPUBOCSNCGTHUZUIEGWVIGJMIDSTOYIYICYMGKZJQZIOMJCFKTRQPFWSIUMGXGPVARPCZJUVRTAKLVRRZWMOEMKFKUVGRTMSWSJUWWSXKJQVZCEEPUSPTXFBLQEWTWSZIEBVJBAAYSAPIWVTKIEOWIUVHMIOVTHKAXHRULTDPJCQIDNAHTJCWYIHPBWBFLRLRTTMATARVTYIFPYLXIVOQWVLBLXDVSYWEZJWMCKSAWKZFWKTLBZHWTBYHNIGBRIAXBVHBRTJIOLVRHSVHRKNPFLXOJSQPVKAQSCUHAMVAWIIJFCDTDLNEXPDGU

**Program after six attempts**

**KEY:** LWAPNILPALIWALARUNRAMMOHANARETHETWOCONTRIBUTORSFORTHISPROJECT
**Plaintext:** AHEFIRSTWELLDOCUMENTEDDESCRIPTIONOFAPOLYALPHABETICCIPHERWASBYSEONBATTISTAALBERTIANDUSEDAMETALCIPHERDISKTOSWITCHBETWEENCIPHLRALPHABETSALBERTISSYSTEMONLYSWITCHEDALPHABETSAFTERSEVERALWORKSANDSWITCHESWEREINDICATEDBYWRITINGTHELETTEROFTHECORRESPONDINNALPHABETINTHECIPHERTEXTLATERJOHANNESTRITHEMIUSINHISWORKPOLYGYAPHIAEWHICHWASCOMPLETEDINMANUSCRIPTFORMBUTFIRSTPUBLISHEDLATEYINVENTEDTHETABULARECTAACRITICALCOMPONENTOFTHEVIGENERECIPHERTOETRITHEMIUSCIPHERHOWEVERPROVIDEDAPROGRESSIVERATHERRIGIDANDPRLDICTABLESYSTEMFORSWITCHINGBETWEENCIPHERALPHABETSTHECIPHERNOWRNOWNASTHEVIGENERECIPHERHOWEVERISTHATORIGINALLYDESCRIBEDBYGIOCANBATTISTABELLASOINHISBOOKLACIFRADELSIGGIOVANBATTISTABELLASOOEBUILTUPONTHETABULARECTAOFTRITHEMIUSBUTADDEDAREPEATINGCOUNTEYSIGNAKEYTOSWITCHCIPHERALPHABETSEVERYLETTERWHEREASALBERTIANDTYITHEMIUSUSEDAFIXEDPATTERNOFSUBSTITUTIONSBELLASOSSCHEMEMEANTTOEPATTERNOFSUBSTITUTIONSCOULDBEEASILYCHANGEDSIMPLYBYSELECTINGHNEWKEYKEYSWERETYPICALLYSINGLEWORDSORSHORTPHRASESKNOWNTOBOTHPHRTIESINADVANCEORTRANSMITTEDOUTOFBANDALONGWITHTHEMESSAGEBELLAZOSMETHODTHUSREQUIREDSTRONGSECURITYFORONLYTHEKEYASITISRELATIVLLYEASYTOSECUREASHORTKEYPHRASESUCHASBYAPREVIOUSPRIVATECONVERSHTIONBELLASOSSYSTEMWASCONSIDERABLYMORESECUREINTHENINETEENTHCEUTURYTHEINVENTIONOFBELLASOSCIPHERWASMISATTRIBUTEDTOVIGENEREDACIDKAHNINHISBOOKTHECODEBREAKERSLAMENTEDTHISMISATTRIBUTIONSAYIUGTHATHISTORYHADIGNOREDTHISIMPORTANTCONTRIBUTIONANDINSTEADNAMLDAREGRESSIVEANDELEMENTARYCIPHERFORHIMVIGENERETHOUGHHEHADNOTHPNGTODOWITHITTHEVIGENERECIPHERGAINEDAREPUTATIONFORBEINGEXCEPTPONALLYSTRONGNOTEDAUTHORANDMATHEMATICIANCHARLESLUTWIDGEDODGSOULEWISCARROLLCALLEDTHEVIGENERECIPHERUNBREAKABLEINHISPIECETHEASPHABETCIPHERINACHILDRENSMAGAZINEINSCIENTIFICAMERICANDESCRIBEKTHEVIGENERECIPHERASIMPOSSIBLEOFTRANSLATIONTHATREPUTATIONWASNVTDESERVEDCHARLESBABBAGEISKNOWNTOHAVEBROKENAVARIANTOFTHECIPHEYASEARLYBUTDIDNOTPUBLISHHISWORKKASISKIENTIRELYBROKETHECIPHERAUDPUBLISHEDTHETECHNIQUEINTHENINETEENTHCENTURYBUTEVENINTHESIXTLENTHCENTURYSOMESKILLEDCRYPTANALYSTSCOULDOCCASIONALLYBREAKTHEJIPHERTHEVIGENERECIPHERISSIMPLEENOUGHTOBEAFIELDCIPHERIFITISUSLDINCONJUNCTIONWITHCIPHERDISKSTHECONFEDERATESTATESOFAMERICAFOYEXAMPLEUSEDABRASSCIPHERDISKTOIMPLEMENTTHEVIGENERECIPHERDURINNTHEAMERICANCIVILWARTHECONFEDERACYSMESSAGESWEREFARFROMSECRETAUDTHEUNIONREGULARLYCRACKEDITSMESSAGESTHROUGHOUTTHEWARTHECONFEKERATELEADERSHIPPRIMARILYRELIEDUPONTHREEKEYPHRASESMANCHESTERBSUFFCOMPLETEVICTORYANDASTHEWARCAMETOACLOSECOMERETRIBUTIONTHEFPRSTWELLDOCUMENTEDDESCRIPTIONOFAPOLYALPHABETICCIPHERWASBYLEONIATTISTAALBERTIANDUSEDAMETALCIPHERDISKTOSWITCHBETWEENCIPHERALWHABETSALBERTISSYSTEMONLYSWITCHEDALPHABETSAFTERSEVERALWORDSANKSWITCHESWEREINDICATEDBYWRITINGTHELETTEROFTHECORRESPONDINGALPOABETINTHECIPHERTEXTLATERJOHANNESTRITHEMIUSINHISWORKPOLYGRAPHPAEWHICHWASCOMPLETEDINMANUSCRIPTFORMBUTFIRSTPUBLISHEDLATERINVLNTEDTHETABULARECTAACRITICALCOMPONENTOFTHEVIGENERECIPHERTHETRPTHEMIUSCIPHERHOWEVERPROVIDEDAPROGRESSIVERATHERRIGIDANDPREDICAABLESYSTEMFORSWITCHINGBETWEENCIPHERALPHABETSTHECIPHERNOWKNOWUASTHEVIGENERECIPHERHOWEVERISTHATORIGINALLYDESCRIBEDBYGIOVANBHTTISTABELLASOINHISBOOKLACIFRADELSIGGIOVANBATTISTABELLASOHEBUPLTUPONTHETABULARECTAOFTRITHEMIUSBUTADDEDAREPEATINGCOUNTERSIGUAKEYTOSWITCHCIPHERALPHABETSEVERYLETTERWHEREASALBERTIANDTRITHLMIUSUSEDAFIXEDPA
