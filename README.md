- 👋 Hi, I’m @esilvestre13
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
esilvestre13/esilvestre13 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->This analysis terminated unexpectedly.

Error in bars[[node]] <- pnorm(GroupThresh$est[GroupThresh$lhs = GroupVars$name[node]]): attempt to select more than one element in integerOneIndex

Stack trace
tryCatchOne(expr, names, parentenv, handlers[[1]])

doTryCatch(return(expr), name, parentenv, handler)

withCallingHandlers(expr = analysis(jaspResults = jaspResults, dataset = dataset, options = options), error = .addStackTrace)

analysis(jaspResults = jaspResults, dataset = dataset, options = options)

ConfirmatoryFactorAnalysis(...)

.cfaPlotPath(jaspResults, options, cfaResult)

jaspBase:::.suppressGrDevice(pathplot <- semPlot::semPaths(object = .cfaLavToPlotObj(cfaResult[['lav']], options), DoNotPlot = TRUE, ask = FALSE, layout = 'tree', intercepts = options$plotmeans, whatLabels = if (!options$plotpars) 'name' else if (options$plotstd) 'std' else 'par', mar = ifelse(rep(is.null(options$secondOrder), 4), c(12, 3, 12, 3), c(6, 3, 6, 3)), edge.color = 'black', color = list(lat = '#EAEAEA', man = '#EAEAEA', int = '#FFFFFF'), border.width = 1.5, edge.label.cex = 0.9, lty = 2,
    title = FALSE))

eval(plotFunc, parent.frame())

eval(plotFunc, parent.frame())

semPlot::semPaths(object = .cfaLavToPlotObj(cfaResult[['lav']], options), DoNotPlot = TRUE, ask = FALSE, layout = 'tree', intercepts = options$plotmeans, whatLabels = if (!options$plotpars) 'name' else if (options$plotstd) 'std' else 'par', mar = ifelse(rep(is.null(options$secondOrder), 4), c(12, 3, 12, 3), c(6, 3, 6, 3)), edge.color = 'black', color = list(lat = '#EAEAEA', man = '#EAEAEA', int = '#FFFFFF'), border.width = 1.5, edge.label.cex = 0.9, lty = 2, title = FALSE)

To receive assistance with this problem, please report the message above at: https://jasp-stats.org/bug-reports
