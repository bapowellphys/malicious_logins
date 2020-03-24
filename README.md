# malicious_logins

This is the data set analyzed in the work "Discovering Malicious Logins as Graph Anomalies" by Brian Powell.  Each row corresponds to one vertex from the login graph of a user.  Vertices are evaluated across 13 measures:

  m1: out degree, k_out
  
  m2: k_out/(w_out + 1), where w_out is the weight of outgoing edges
  
  m3: in degree, k_in
  
  m4: k_in/(w_in + 1), where w_in is the weight of incoming edges
  
  m5: local clustering coefficient
  
  m6: Katz centrality
  
  m7: ego degree 
  
  m8: w_out
  
  m9: w_in
  
  m10: degree, k
  
  m11: eccentricity/(ego degree + 1)
  
  m12: eccentricity/(w_out + 1)
  
  m13: eccentricicty
  
This data set is derived from the login graphs of 89 users.  Each user has between 1 and a few dozen login graphs.
