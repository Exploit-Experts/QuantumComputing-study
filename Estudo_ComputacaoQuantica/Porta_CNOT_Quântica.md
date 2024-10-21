A porta **CNOT** (Controlled-NOT) atua em dois qubits, sendo uma contraparte quântica do **XOR** clássico. Ela age dependendo do valor do qubit de controle: se o controle estiver em |1⟩, inverte o estado do qubit alvo; se estiver em |0⟩, não faz nada. A diferença no caso quântico é que tanto o qubit de controle quanto o alvo podem estar em superposição de estados. A transformação da porta CNOT é descrita por:

- |00⟩ → |00⟩
- |01⟩ → |01⟩
- |10⟩ → |11⟩
- |11⟩ → |10⟩

Contudo, a sensibilidade dos qubits à superposição e o impacto de ruídos e superaquecimento dificultam o desenvolvimento de computadores quânticos práticos.

semelhante ao **XOR** clássico, Ela age sobre dois qubits: um **qubit de controle** e um **qubit alvo**. Se o qubit de controle estiver no estado |1⟩, a porta **CNOT** inverte o estado do qubit alvo (por exemplo, de |0⟩ para |1⟩). Caso o qubit de controle esteja em |0⟩, a porta não faz nada ao qubit alvo.

A grande diferença entre a **CNOT quântica** e a clássica é que, na computação quântica, ambos os qubits podem estar em uma **superposição de estados**. Isso significa que a porta **CNOT** pode operar sobre combinações de estados, o que gera a transformação de superposições quânticas, uma característica fundamental para criar algoritmos quânticos mais poderosos.

A operação da porta **CNOT** pode ser esquematizada da seguinte forma:

- Se os qubits de entrada forem |00⟩ ou |01⟩, eles permanecem inalterados.
- Se os qubits de entrada forem |10⟩ ou |11⟩, o qubit alvo é invertido.