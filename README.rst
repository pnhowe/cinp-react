Deporcated: use the npm version with react, it also has a typescript header


CInP client for react
======================

Example usage::

  import CInP from './cinp';
  cinp = new CInP( host );
  cinp.describe( '/api/v1/' ).then( ( result ) => alert( result.type ) );
