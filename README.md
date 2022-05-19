# Terra LUNA UST Revival Plan Analysis


Please refer to the latest [revival plan proposal](https://agora.terra.money/t/terra-ecosystem-revival-plan-2-updated-and-final/18498)

Proposed Token Distribution:

* Community pool: 25%
    * Controlled by staked governance
    * 10% earmarked for developers
* Pre-attack LUNA holders: 35%
    * All bonded / unbonding Luna, minus TFL at “Pre-attack” snapshot; staking derivatives included
    * For wallets with < 1M Luna: 1 year cliff, 2 year vesting thereafter
    * For wallets with > 1M Luna: 1 year cliff, 4 year vesting thereafter
* Pre-attack aUST holders: 10%
    * 500K whale cap - covers up to 99.7% of all holders but only 26.72% of aUST
    * 15% unlocked at genesis; 85% vested over 2 years thereafter with 6 month cliff
* Post-attack LUNA holders: 10%
    * Staking derivatives included
    * 15% unlocked at genesis; 85% vested over 2 years thereafter with 6 month cliff
* Post-attack UST holders: 20%
    * 15% unlocked at genesis; 85% vested over 2 years thereafter with 6 month cliff

It is possible to calculate some useful insight base on the above information.

Detailed analysis please refer to the attached [notebook](analysis.ipynb).