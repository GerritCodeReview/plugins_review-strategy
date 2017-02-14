load("//tools/bzl:plugin.bzl", "gerrit_plugin")

gerrit_plugin(
    name = "review-strategy",
    srcs = glob(["src/main/java/**/*.java"]),
    resources = glob(["src/main/**/*"]),
    gwt_module = "com.googlesource.gerrit.plugins.reviewstrategy.ReviewStrategy",
    manifest_entries = [
        "Gerrit-PluginName: review-strategy",
        "Gerrit-Module: com.googlesource.gerrit.plugins.reviewstrategy.Module",
        "Gerrit-HttpModule: com.googlesource.gerrit.plugins.reviewstrategy.HttpModule",
    ],
)
