ask several questions of each of the following types:

1. **descriptive** - these are very basic questions about the nature of the data, that do not require and statistical computing (eg, sample size, # of features, # of nans, etc.)
2. **exploratory** - these are summary statistics about your data, things like averages, correlations, clusters, outliers, etc.
3. **inferential** - these are hypothesis tests, as explained in class, have the following form:

x_i ~iid F_X \in \mathcal{F}

H0: f(F_X) \in \mathcal{F}_0 \subset \mathcal{F}
HA: f(F_X) \in \mathcal{F}_1  \subset \mathcal{F}

where \mathcal{F}_0 \cap \mathcal{F}_1 = \empty

so, specifying a hypothesis test requires specifying: X, \mathcal{F}, \mathcal{F}_0, \mathcal{F}_1, and f().

4. **predictive** - these are classifacation, regression, or structured regression problems, that have the following form:

given (X_i,Y_i), for i \in [n]
find 

argmin  E || g(X; X_1, \ldots, X_n) - Y ||   
such that g \in \mathcal{G}

ideally specify the joint distribtuion F_{XY} such that \mathcal{G} in unbiased.
this requires, therefore, explicitly stating ones assumptions.

5. **causal** - these are questions about which entities of observation cause which other entities.  in other words, this is more than just prediction, it is asking whether the predictive variables are causal, or merely correlative.

6. **mechanistic** - this is about mechanism, which always means explaning observations at one "level" of description via the activities of a "lower" level of description, 
eg, thermodynamics causes genetics causes protein expression causes anatomy & physiology causes perception causes behavior etc.



