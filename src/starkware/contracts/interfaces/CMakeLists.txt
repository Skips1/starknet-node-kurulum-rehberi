python_lib(solidity_contracts_interfaces_sol
    PREFIX starkware/contracts/interfaces
    FILES
    BlockDirectCall.sol
    IFactRegistry.sol
    IIdentity.sol
    IQueryableFactRegistry.sol
)

python_lib(governance_interface_sol
    PREFIX starkware/contracts/interfaces
    FILES
    MGovernance.sol
    MOperator.sol
)

python_lib(solidity_contract_initializer_sol
    PREFIX starkware/contracts/interfaces
    FILES
    ExternalInitializer.sol
    ContractInitializer.sol
    ProxySupport.sol
)
