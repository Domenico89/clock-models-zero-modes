Solutions of the zero mode expansion for \theta=\pi/12 and \phi=0, up to the 5th order (that is operator acting on chain of length 6). Note that the solution is not correctly normalized. 
To use the files initialize it in a Mathematica Notebook through the Get function.

For example, in order to create the solution \psi^{(2)}, write in a Mathematica nootebook 

pos=<<"DirectoryPath/Psi2qPi12Pos.txt";
val=<<"DirectoryPath/Psi2qPi12Val.txt";
psi2q=makeVector[pos,val,3,3];

pos=<<"DirectoryPath/Psi2pPi12Pos.txt";
val=<<"DirectoryPath/Psi2pPi12Val.txt";
psi2p=makeVector[pos,val,3,3];

psi2=psi2q+psi2p
