# CharNeRF: 3D Character Generation from Concept Art [1]
For the research project on Procedural Content Generation for Games using Machine Learning Techniques in NUS/Riot Games Singpapore.
The published paper can be found [here](https://arxiv.org/pdf/2402.17115).
Note: this is an empty repository created for evaluator to see our qualitative results. Actual repository is private currently.

## Table of Contents

- [Visuals](#visuals)
- [Reference](#reference)

## Visuals
NeRF reconstruction from 3 source views (concept art views)
credit: https://www.mixamo.com/

<p float="left">
  <img src="https://user-images.githubusercontent.com/59797323/228722325-e5314328-ef53-432e-8989-423d81800d00.gif" width="200" />
  <img src="https://user-images.githubusercontent.com/59797323/228723492-2725de90-9fb8-40c5-84b3-b1c90894dc54.gif" width="200" />
  <img src="https://user-images.githubusercontent.com/59797323/228723171-4d877287-bb71-4f0b-9a5a-1bd5243c074e.gif" width="200" />
  <img src="https://user-images.githubusercontent.com/59797323/228723865-867c0327-8922-430d-8274-384bead22d21.gif" width="200" />
</p>

<p float="left">
  <img src="https://user-images.githubusercontent.com/59797323/228724094-b32291a4-1076-4d1c-bc77-e867059ae23b.gif" width="200" />
  <img src="https://user-images.githubusercontent.com/59797323/228724294-b6b57bb2-fa13-4d06-b6ea-28a2c5ba1fa8.gif" width="200" />
  <img src="https://user-images.githubusercontent.com/59797323/228726448-821b840c-51d1-4833-9111-aa9d15a44c4a.gif" width="200" />
  <img src="https://user-images.githubusercontent.com/59797323/228725592-106cb088-83d3-4c64-a53d-aa67740850ba.gif" width="200" />
</p>

<p float="left">
  <img src="https://user-images.githubusercontent.com/59797323/228750779-1284977c-33e1-433b-be9f-8a1efff10b81.gif" width="200" />
  <img src="https://user-images.githubusercontent.com/59797323/228750799-9e0cc713-c535-407e-bc3e-3b1158619205.gif" width="200" />
  <img src="https://user-images.githubusercontent.com/59797323/228762866-95b560ae-b90c-463d-86e2-3624429b107f.gif" width="200" />
  <img src="https://user-images.githubusercontent.com/59797323/229602754-aac789ae-e2f9-4378-84b5-1ad3a9a6dd98.gif" width="200" />
</p>


Results from sketches from online resources:
Left three images are input sketches. The gif is the NeRF rendered result

credit/source: https://www.deviantart.com/glitcher/art/Mega-Man-Volnutt-model-sheet-438603492
<p float="left">
  <img src="https://user-images.githubusercontent.com/59797323/230574607-cb095e1c-fce5-496c-a385-19de644cd1ea.png" width="200" />
  <img src="https://user-images.githubusercontent.com/59797323/230574603-a750944d-e980-45f5-ab3f-0bd7a2109867.png" width="200" />
  <img src="https://user-images.githubusercontent.com/59797323/230574593-5e3d40f3-7306-4b34-8552-e8471876c01f.png" width="200" />
  <img src="https://user-images.githubusercontent.com/59797323/230568541-3cc0bd9c-8d35-4225-9bdb-c8c95fcca921.gif" width="200" />
</p>

credit/source: https://www.deviantart.com/glitcher/art/Zero-Suit-Samus-model-sheet-436501754
<p float="left">
  <img src="https://user-images.githubusercontent.com/59797323/230575081-addbef16-8bca-44ff-84fc-a7223185cf9a.png" width="200" />
  <img src="https://user-images.githubusercontent.com/59797323/230575087-8dedc37a-e1cb-4c68-8dd1-c962aa065b6d.png" width="200" />
  <img src="https://user-images.githubusercontent.com/59797323/230575084-d3e8367d-36f0-4abc-9934-7e5603d21ba8.png" width="200" />
  <img src="https://user-images.githubusercontent.com/59797323/230579025-670bd08f-ce43-435d-be57-fc5cdfb9f2b0.gif" width="200" />
</p>

credit/source: https://www.pinterest.com/pin/786089309994518388/
<p float="left">
  <img src="https://user-images.githubusercontent.com/59797323/230715404-9788d90a-57a3-41c7-b545-f001d05dd169.png" width="200" />
  <img src="https://user-images.githubusercontent.com/59797323/230715407-7c755576-6eb4-43da-928d-f5425474c05f.png" width="200" />
  <img src="https://user-images.githubusercontent.com/59797323/230715408-eaa3bf34-9706-4084-a3fd-6fa7a4d4d236.png" width="200" />
  <img src="https://user-images.githubusercontent.com/59797323/230715219-b692231f-a0fd-4901-9032-7e630a6dfb36.gif" width="200" />
</p>

credit/source: https://www.artstation.com/artwork/RnkVEm
<p float="left">
  <img src="https://user-images.githubusercontent.com/59797323/230575945-c9fbe366-e61b-430d-ae91-42adfefb0d78.png" width="200" />
  <img src="https://user-images.githubusercontent.com/59797323/230575953-bb75959b-25ad-4abc-86f3-685b286f1af2.png" width="200" />
  <img src="https://user-images.githubusercontent.com/59797323/230575955-c4afb94d-7df2-4c0d-915d-b66a2d490880.png" width="200" />
  <img src="https://user-images.githubusercontent.com/59797323/230697785-a943b11f-82f1-41c7-bde6-1c9b98649a2e.gif" width="200" />
</p>

credit/source: https://jakeneal.wordpress.com/2011/10/13/character-t-pose/turnaround2/
<p float="left">
  <img src="https://user-images.githubusercontent.com/59797323/230576936-2ba43926-d124-46fd-be2b-290a7ed9880d.png" width="200" />
  <img src="https://user-images.githubusercontent.com/59797323/230576938-f602b739-40d1-4c63-b38e-0918ff709f66.png" width="200" />
  <img src="https://user-images.githubusercontent.com/59797323/230576943-e1382656-c63c-4af1-af2c-26ca28a7767f.png" width="200" />
  <img src="https://user-images.githubusercontent.com/59797323/230697830-213fcea8-9adc-4327-9e7f-8504ee83c918.gif" width="200" />
</p>

credit/source: 
https://www.deviantart.com/glitcher/art/Beck-Model-Sheet-399333656
<p float="left">
  <img src="https://user-images.githubusercontent.com/59797323/230577123-b9566900-45ae-48dc-9ea0-84ac3bcf55b2.png" width="200" />
  <img src="https://user-images.githubusercontent.com/59797323/230577127-40d830c1-c74b-4488-909b-c75434f12123.png" width="200" />
  <img src="https://user-images.githubusercontent.com/59797323/230577132-f5d73cce-ac0f-47a1-9bb5-c8e3d826a941.png" width="200" />
  <img src="https://user-images.githubusercontent.com/59797323/230697848-8276b989-0d83-4168-8b88-5016efaa3660.gif" width="200" />
</p>

credit/source: https://www.pinterest.com/pin/189784571789670978/
 <p float="left">
   <img src="https://user-images.githubusercontent.com/59797323/230576820-41aff18f-2813-4060-a999-28662c465f97.png" width="200" />
   <img src="https://user-images.githubusercontent.com/59797323/230576822-e6c95832-26f2-4a89-b8d4-7c2920dd1a24.png" width="200" />
   <img src="https://user-images.githubusercontent.com/59797323/230576825-59c64b33-6fe7-439b-822f-03cfb44c080c.png" width="200" />
   <img src="https://user-images.githubusercontent.com/59797323/230698099-51d82ed7-a5cd-47b6-983d-0b87c793e63d.gif" width="200" />
 </p>
 
 credit/source: https://civitai.com/images/212764?modelId=3036&postId=110853&id=3036&slug=charturner-character-turnaround-helper
  <p float="left">
   <img src="https://user-images.githubusercontent.com/59797323/230715321-96601895-8c25-42fc-84be-0718ce6e77a3.png" width="200" />
   <img src="https://user-images.githubusercontent.com/59797323/230715322-477ee1fc-2a42-4552-bb48-f5581415f967.png" width="200" />
   <img src="https://user-images.githubusercontent.com/59797323/230715323-bb9ca314-5eeb-4b99-afba-6934b48a230d.png" width="200" />
   <img src="https://user-images.githubusercontent.com/59797323/230715473-22e576c2-caa6-4213-98da-dd1fb835db62.gif" width="200" />

 </p>
 
 credit/source: https://www.pinterest.com/pin/786089309994518388/
<p float="left">
  <img src="https://user-images.githubusercontent.com/59797323/230575352-37d0e717-15c3-4154-ac1a-fae2225f735f.png" width="200" />
  <img src="https://user-images.githubusercontent.com/59797323/230575348-8a04d562-9ae1-4b03-a421-0f15a83e42d1.png" width="200" />
  <img src="https://user-images.githubusercontent.com/59797323/230575342-25b9763b-f74c-4ab4-aa3e-fb9db8ab2523.png" width="200" />
  <img src="https://user-images.githubusercontent.com/59797323/230697757-c2c61bde-8f2b-4a47-9c5b-e7477a928e64.gif" width="200" />
</p>

## Reference
[1]: Chu, E., Chen, Y., Raissi, C., & Bhojan, A. (2024). CharNeRF: 3D Character Generation from Concept Art. In *2024 IEEE International Conference on Artificial Intelligence and eXtended and Virtual Reality (AIxVR)* (pp. 185–194). IEEE. [http://dx.doi.org/10.1109/AIxVR59861.2024.00031](http://dx.doi.org/10.1109/AIxVR59861.2024.00031).

